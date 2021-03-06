---
title: "The Glimcap Part 3"
date: 2021-02-11T08:00:00-04:00
author: "Heiwa & RibenaBerri"
---

Welcome to our recap of Tuesday's team meeting from Febraury 9th 2021. We have some exciting news to share in regards to merch, improvements on the site, and a cool new test we performed on the site. There have been some significant developments over this week so keep reading on for more info.

<!--more-->

## Glimesh’s Growth

Our growth is remaining consistent throughout the week and Instagram even had a nice little spike. We are currently focused on mainly Twitter so seeing the spike in growth from Instagram is a sign that users are sharing us on platforms even though we may not be completely active on them. This is encouraging as it's a sign of just how much the community is spreading and the love everyone has for us.

Also we have hit that next 1,000 mark hitting over 12,000 users on the site this week.


| <br/> | This Week | Last Week | Diff |
| - | - | - | - |
| Discord | 2,505 | 2,465 | 40⬆ |
| Twitter | 4,459 | 4,389 | 70⬆ |
| Reddit | 272 | 269 | 3⬆ |
| Instagram | 326 | 305 | 21⬆ |
| Facebook | 201 | 193 | 8⬆ |
| <br/> | <br/> | <br/> | <br/> |
| Users | 12,299 | 11,847 | 452⬆ |
| Apps | 58 | 50 | 8⬆ |
| MRR | $360 | $310 | $50⬆ |
| Support Tickets | 12 | 7 | 5⬆ |

![](https://lh4.googleusercontent.com/wVYuX0rx9t-fCV_K0h_g8KRaOl1-Q6hwL1tjM8-vLIJA4Q4iksVKNCLUlhRxkt8fe1BOXFNV_rgyDn-Ifs6SimpxUF8mSJ15gZCgCWumxepDm4uurCLrd6RcbGj6ipYR6o9PoqzW)![](https://lh5.googleusercontent.com/x-L1oxeEyYW_u-zma7M83uKDfrMj7qjaovJN3NqCQbdsgkNPTq_Q-4caan_qasyeT7PLNcoX3Yf4oWsTwaQ6RqJl_bThtJb_TZTd_L6MwMpqx0jB3jVNj1NKOuHrcZmiMmVyhNeY)

![](https://lh3.googleusercontent.com/eSxGEBCi5We7phnpwVw9jUC_OSxSX2kZiYu1f3SxdGqy5BxAwHQ1sWb9IAW9BwCKCeqXsxd_ldGj3xfVrn1KtBkbqcPTCmLP8eAvfTqMfKN_ABnXR8AH_gqoCEZZOtrbLSSzlmQH)


## Dev Wins


## New follower Box

Many thanks to [Mja](https://glimesh.tv/mja00/profile) who has updated the following chat alert. You may have remembered in the past that a new follower alert looked like every other message. Anyone could copy and paste the message and make it appear that they had followed. Now the messages have a slight purple outline to distinguish them from regular messages.

![](https://lh3.googleusercontent.com/AxlsWXq1aRY2OwSbKl5eXTS-l_BCzY6G57vPduk3SP-X9DHZcL1Op1osVTdMY-2IRkUbZmQWC1tBgrkaA-IKRbEeBj6DXRNZ2vEtLHUtR2dss8All66xn3y9JirUbrvHy2li7o3N)


## Global Edge Location Routing Setup

Thanks to [Ember](https://glimesh.tv/Ember/profile) we’ve had all our Edge Location routes setup. What this means is that when you connect to Glimesh we already will have the closest Edge location mapped out for you ensuring you get the lowest latency server possible at that time.


## Mature Content Warning

We’ve also established a Mature Content Warning. This will be set in place for ToS reasons, safety of viewers, and safety for your stream.This little feature will warn you before entering a stream that the streamer has mature content that way there are no surprises.

![](https://lh3.googleusercontent.com/-Tw_uKMgBI74N95ExLK0NDrz3PbDPUe_S1DLCRMG_bDzTU-AdoJ9rGWgGIKXRzwE7L1FzR1tgnCF9aBxQQEpqhB3DJwMojqq2aODeTrjKgdDj2mRNp5B3suJjyNNXTUcPL6zOpo-)


## Janus FTL Rewrite

[Hayden](https://glimesh.tv/HammyCheesy/profile) has once again been hard at work on the FTL Janus rewrite. This improves code quality, architecture, and testability. There are a series of improvements from this refactor for RTP packets, it more intelligently sends NACKs for groups of missing packets instead of one-at-a-time, and it calculates additional stats such as running average bitrate. The server CPU’s saw improvements of up to 50% after this rework which means more efficiency from the code.

![](https://lh6.googleusercontent.com/8pric3LHork2Uty0JN5m5PClAz2Y6ntK6cCoM1AWYWRXedC22Ax9-VnCr64TdY5rgVAAKxpXQBu_ikXpw-p8afGGkMRabaoWkDHpXFiYETckaiUGAMOhOtRX7a95vRirgWZB67Ww)


## Payouts

Payouts are improving. [Clone](https://glimesh.tv/clone1018/profile) has worked hard on refactoring and improving our payment code. We are hoping that at Alpha launch we will be able to support 33 countries. [https://stripe.com/docs/connect/cross-border-payouts](https://stripe.com/docs/connect/cross-border-payouts) here is a full list of those countries. This is all tax pending as we are still trying to determine our responsibility but we are one step closer to being able to support more countries hopefully for the Alpha launch.


## Test Streams

On Tuesday night we got an official ingest stream test going. We had around 11-13 streams going on at once. And while there were some hiccups we saw mostly stable streams coming in from all over the world. The servers handled the load great and it gave us some pretty good ideas of how many people we will be able to reasonably handle on a server.

![](https://lh5.googleusercontent.com/48PGdE9TOqy98YB2eTWqn4QE9cpRZ3-rIu1svbbf7ux1_omVvXmvLiExN-Xq0C8EFDhU3vIgZYEBv8wqmaCGLX6nC6TYbcVdHizdzRCtydWXK3idOjri-WTt-IscvThmysmD58N4)

## Community Wins


## Day 1 Streaming Guide

The Design Team has been hard at work creating a Day 1 Stream guide. Here is a little sneak peak. If you are signed up on the site you should be receiving one of these in your email. This document will give you a little insight as to what you need to do to get started with streaming on Glimesh.

![](https://lh3.googleusercontent.com/DJvUiYMXkOosQ2C8_LSThbFbKNt9ai69MNCbEUpsAyHOboXc50p3D47AcXV3PWwkd3eW64AS-dp4IubSOiSHPe7oyg4zkqpp_pa6dzS1R2HGSYWbNHgpvUffm3PUVYDfOFN6OhPP)

## Merch

Our last big community win is Merch is coming soon! We will be releasing merch for sale sometime this week or next. We have soft cotton T-Shirts branded with Glimesh on the front and the sleeve: Sizes: S, M, L, XL, 2XL, 3XL (more coming soon!)! Now here’s the catch. Due to some unfortunate timing between when we collect the money for the sale and when we pay for the shirts we will have to do limited weekly batches. Week 1 will only be opening the shop for 50-100 shirt sales TBD. If you miss the first wave though don’t worry, you will be able to get a chance the next week around. We are aiming to remove this limit eventually once we get the financial aspect all sorted out.

Now the next question - How Much?

Shirts will be $23 for all sizes and $5 for shipping anywhere in the world. No guessing just one price for both. Merch is dropping today (February 11th) at noon so check it out.

![](https://lh6.googleusercontent.com/gGtN1ok84LfryBJfTlOoRf-D2aOq7i5QpZFuqho3msziFI-7ptFGTOUnDDzuYndJnJxKJn2IqM-rfEzzEdRkUa-jEoY6SXqLxzrEwSISxL7PdE0DM7XA5Gdx7KMJUjVi11kUgRKW)![](https://lh5.googleusercontent.com/lvNh5yoQ5dWNy3uVB5o2BjNfbsJHGqeejEyNAU1x7DbVcs0OWQ9huhxPpWLk4Bk8RsgGuBlG1_NIW3Z5wz2ivglgbGdSqsoxRnKIXjIEvzGIwcWYXUDxzuGcxxvwj0wXrvrLIhke)


## Challenges

Our challenges still remain mostly the same, but we are making progress. Foreign tax is still an issue we are researching but we are making ground. 3D secure is in the works with the new payment code being written and the DMCA / Licensing aspects are being worked on as well.


## Roadmap Update

![](https://lh4.googleusercontent.com/trb6YpYEHYMOx9IeFvQ4XVmSIfq7FtBFLrF5-6TUWHjZ3uKYbi7lTdjnFPFloBH1U6_tSitDlspLBxQJGoXdIU-k_7J-te4FOLpYkghwHZy-lX0TMUBQcIpOAHAYOJAaXaZ_BVTj)

We are just about ready to cross off these last two pieces. The stream testing that was done has helped put some action items in place to cross off that stream stability aspect and the payment controls are nearing their end. These are not quite finished yet but we are getting close to that Early 2021 stretch. Keep watching for that announcement.


## GlimFact of the Week

Glimesh takes a 50/50 split on Subscription payouts. But did you know that we pay all the processing fees? That means when we collect the $5 sub you get 50% for $2.50.

![](https://lh3.googleusercontent.com/ge8aKqBNgPCmhwBCx-ED4-OogpFVsBb5S7rNAlr7VpdfBuE0rwwbC3KK0ag9E2SSvRxi3fxp4Tr2rNNGYmWCEt7Xly8BCjvVi5ts1a5tR83ZUGXytcAMUGhcrz7noQjeJr0DmdOt)

*Written by RibenaBerri and Heiwa if you'd like to join in contributing or have any feedback to these Recaps please reach out in the [Discord](https://discord.gg/glimesh) under #business.'***
