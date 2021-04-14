---
title: "Security Incident - OAuth Key Exposure"
date: 2020-11-14T08:00:00-04:00
---

Hello everyone,

On Friday November 13rd 2020 at 11:30 AM EST we were informed of a potential security concern for accessing private developer information. The issue was caused by permissions checks being ignored on the Developer Applications page on our website. This could lead to a situation where you could plainly read another developer applications's oauth client id & client secret. As of 1:14PM EST that same day, the access was prevented and the issue resolved.

<!--more-->

Our ranking of this security issue is: Low

##### No passwords, emails, or any other private user data that is stored on Glimesh has been compromised or was at risk during this incident. There is also zero risk to any payment information being compromised or at risk from this incident.
Glimesh does not store, or plainly read any payment information (credit cards, bank details, etc) anywhere on the website as we utilize Stripe to handle all payments.

We choose Low for this issue as we have not yet developed any API endpoints that allow any users to edit, change, or delete any user content. Nor can any of the API endpoints access any data the user can not normally access via unauthenticated means. The only perceivable impact of this security incident would be that a user could have used a service oauth application to obtain user stream keys, however since we are not live, the stream keys would be unusable. [Here is a section from the OAuth RFC about compromised OAuth Client Secret](https://tools.ietf.org/html/rfc6819#section-4.1.1) if you want to read more.

What was accessible:
* OAuth Client ID - Considered public information, and is used to build login URLs, and is normally public for all users.
* OAuth Client Secret - Similar to a password, they allow access to our API.
* Stream Key - Key required in OBS or similar to authenticate your stream.

At this time we have fixed the issue, and are moving forward with a plan to cycle all OAuth keys & stream keys across the platform. If you are a developer on the platform with an app, you should have received an email instructing you on the key rotation. If all keys are not rotated by Saturday November 14th 2020 @ 10PM EST, we will be forcibly rotating them. In addition, we will be rotating all stream keys for all users ahead of our launch. You can find your applications at https://glimesh.tv/users/settings/applications

We merged two pull requests to resolve this issue: [Check for OAuth App & Mod Ownership](https://github.com/Glimesh/glimesh.tv/pull/255) and [Add OAuth & Stream Key Rotation](https://github.com/Glimesh/glimesh.tv/pull/256)

I want to thank Ben ([@ponkey364](https://twitter.com/ponkey364)) for responsibly disclosing this security issue as soon as they found it, and providing great information on the details of the issue. If you are interested in learning more about Glimesh's security policy, please [check out our GitHub](https://github.com/Glimesh/glimesh.tv/blob/f238338d6d9e4351cff82e89c89f5052a4c2b3dd/SECURITY.md).

It's important to not underestimate the importance of our users security, privacy, and their trust for our platform. We will be making serious changes to underlying permission modeling and to our pull request processes for team members, and open source collaborators as a whole. I apologize for this issue, and I will do my best to prevent issues like it from happening again.

Thanks,

Luke Strickland

Founder @ Glimesh