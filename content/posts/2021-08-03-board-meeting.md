---
title: "Board Meeting 08/2021"
date: 2021-08-04T08:00:00-04:00
author: "Glimesh Team"
---

Hello everyone, and welcome to the August board meeting for Glimesh. In July we officially hit the one year mark of our original charity stream that we did with Ikaros on July 22nd, and it’s been a very exciting year so far. The future's looking bright, the past two months have been a lot of work and preparation to bring the alpha roadmap forward and I’m excited to share what we’ve been working on with you today.

Called to order: August 3rd, 2021 / 7:00 PM EDT

### YouTube Recording
You can find a YouTube recording of this video here: [https://www.youtube.com/watch?v=HGdFxMhv1iA](https://www.youtube.com/watch?v=HGdFxMhv1iA)

### Company Attendance
Luke Strickland

## Agenda

### Executive Report
Hello everyone, and welcome to the August board meeting for Glimesh. In July we officially hit the one year mark of our original charity stream that we did with Ikaros on July 22nd, and it’s been a very exciting year so far. The future's looking bright, the past two months have been a lot of work and preparation to bring the alpha roadmap forward and I’m excited to share what we’ve been working on with you today.

My singular focus for Glimesh has been the development of the mobile app, as well as investigating ways of improving our video infrastructure to deliver all of our users more stable experiences. Our core belief is that with the mobile app released and video improvements implemented, we’ll have everything we need to start effective marketing campaigns targeted towards bringing new viewers and streamers to the platform. The pendulum of the past two months is finally in full swing, and we’re ready to unblock some of the requirements to get the mobile app in your hands.

On August 20th, we’ll be pushing out a [new system for handling our OAuth](https://build.glimesh.tv/t/oauth-migration/65) app authentications on the platform, along with our new API. These two blockers have prevented user testing of the mobile app, and with those out of the way we’ll be able to offer you the ability to help test our mobile app. Shortly after we’ll also be rolling out preliminary testing of our new low-latency implementation of the RTMP protocol, which will bring packet loss stability to those who require it, and full restreaming / other app support for those who need it. In our early testing with the low latency RTMP implementation, we’re seeing only minimal delays on top of our existing FTL infrastructure. This new implementation should give us a good platform to deliver more optimized video to our mobile devices when the app is ready to go public.

We’ve also been working on improving the way we collaborate on Building Glimesh. As you know Glimesh is a very unique project that exists truly as “built by the community, for the community”. We’re an open company, so all of our work happens in public, all of our decisions are consumable & available. Today we’re introducing our new Building Glimesh forum, this new platform offers all of our contributors a more organized & efficient way to work on Glimesh. It gives all of our contributors easier access to participate in the conversation regardless of free time, time zones, platform choices, or any other blockers. I invite everyone who is even mildly interested in helping to build Glimesh to check out [our new forum](https://build.glimesh.tv/) and see how you can participate in the conversation.

As I close this executive summary, I want to use my final words to call on the contributors of Glimesh and our community at large to make this project what we’ve all known it could be. It’s time to show the world we’re building something revolutionary here, and we’re not doing it at the expense of our beliefs, our users, or our product. Thank you truly for your support so far, and I hope we can continue to build a platform you believe in.

-   Luke Strickland (clone1018 on Glimesh)
    

### Metrics
Social media has stagnated for the most part, with all core efforts focused on development. We’ve pushed out a couple of Tweets, but have been mostly silent on other platforms.

![](https://lh5.googleusercontent.com/Pcp2Otey0TWpymiyaWNjOIJTwfuNUp101uEJ3rFpqkGOgcpAScvsweQIf8yiNZVwOQ6s_SsVt3h77WNSSw_xIYt5sxb7NSfIGVHHiCUCyz-3YkdKgm1mOBpTX0ZQP35R4ODeo4g7 "Chart")

In the month of July, we’ve seen a continuation of our downward trend on both average streamers and peak viewership. We’ve been hovering around the usual average of 245 unique streamers each week, however we’ve had 60 new streamers try us out in the month of July. Overall we saw a 18% drop in unique visitors from June to July.

![](https://lh4.googleusercontent.com/eIv-VajAl13ipIIzjcr-ngsjGyzxv1NxHVx5JkvYWCurA6yPwtMmukaFv9TDrYFKEMZCjIIXcj24OwyhqmluhXkQOl5fWgupKhwLxTszrVM97dDVw0QaDrQjqiSlhcKiaOm1A8c- "Chart")

|                 | February 2021 | March 2021 | April 2021 | May 2021 | June 2021 | July 2021 |
|-----------------|---------------|------------|------------|----------|-----------|-----------|
| Social Media    |               |            |            |          |           |           |
| Discord         | 3,667         | 6,198      | 5,936      | 5,652    | 5,296     | 4,981     |
| Twitter         | 5,944         | 9,131      | 9,206      | 9,264    | 9,238     | 9,133     |
| Reddit          | 366           | 564        | 584        | 606      | 613       | 621       |
| Instagram       | 533           | 1,167      | 1,190      | 1,176    | 1,178     | 1,170     |
| Facebook        | 266           | 581        | 609        | 624      | 636       | 642       |
| TikTok          |               |            |            | 67       | 75        | 81        |
| Guilded         |               |            |            | 174      | 177       | 191       |
|                 |               |            |            |          |           |           |
| Website Traffic |               |            |            |          |           |           |
| Unique Visitors | 58,100        | 199,000    | 63,000     | 38,800   | 30,300    | 25,600    |
| Total Pageviews | 625,000       | 2,600,000  | 484,000    | 316,000  | 219,000   | 184,000   |
  

### Finances
Our finance categories are split up into two categories: Software as a Service (generally recurring) and Physical Sales (generally one time). This financial spreadsheet breaks down those two categories, in addition to providing a traditional P&L itemization. Overall Glimesh is in a good financial position and we expect revenue to pick back up with the launch of our mobile app.

|                          | February 2021 | March 2021    | April 2021   | May 2021     | June 2021    | July 2021    |
|--------------------------|---------------|---------------|--------------|--------------|--------------|--------------|
| Software as a Service    |               |               |              |              |              |              |
| Gross Subscriptions      | $ 2,645.00    | $ 12,550.00   | $ 9,510.00   | $ 7,540.00   | $ 5,960.00   | $ 5,075.00   |
| Streamer Payouts         | $ (12.50)     | $ (2,795.34)  | $ (2,036.12) | $ (1,665.89) | $ (1,451.03) | $ (1,044.30) |
| Charges Fees             | $ (136.27)    | $ (892.05)    | $ (672.37)   | $ (538.23)   | $ (429.08)   | $ (360.70)   |
| Refunds                  | $ (25.00)     | $ (30.00)     | $ (40.00)    | $ (30.00)    | $ (5.00)     | $ -          |
| Connect Fee (prev month) | $ (14.70)     | $ (71.51)     | $ (1,230.11) | $ (1,074.47) | $ (916.02)   | $ (772.94)   |
| Subscription Expenses    | $ (188.47)    | $ (3,788.90)  | $ (3,978.60) | $ (3,308.59) | $ (2,801.13) | $ (2,177.94) |
| Subscription Revenue     | $ 2,456.53    | $ 8,761.10    | $ 5,531.40   | $ 4,231.41   | $ 3,158.87   | $ 2,897.06   |
|                          |               |               |              |              |              |              |
| Physical Sales           |               |               |              |              |              |              |
| Merch Sales              | $ 5,272.00    | $ 1,627.00    | $ -          | $ 135.00     | $ 56.00      | $ 56.00      |
| Printful Fee             | $ (3,767.72)  | $ (1,133.29)  | $ (43.97)    | $ (91.78)    | $ (46.77)    | $ (65.17)    |
| Shopify Fee              | $ (30.74)     | $ (30.74)     | $ (30.74)    | $ (30.74)    | $ (30.74)    | $ (30.74)    |
| Merch Expenses           | $ (3,798.46)  | $ (1,164.03)  | $ (74.71)    | $ (122.52)   | $ (77.51)    | $ (95.91)    |
| Merch Revenue            | $ 1,473.54    | $ 462.97      | $ (74.71)    | $ 12.48      | $ (21.51)    | $ (39.91)    |
|                          |               |               |              |              |              |              |
| Expenses                 |               |               |              |              |              |              |
| DO Credits               |               | $ 8,042.78    | $ 3,123.86   | $ 1,074.70   | $ -          | $ -          |
| DO Infra                 |               | $ (2,285.04)  | $ (1,483.81) | $ (1,459.07) | $ (1,438.24) | $ (1,315.69) |
| DO Bandwidth - Overage   |               | $ (2,498.91)  | $ (565.35)   | $ -          | $ -          | $ -          |
| IaaS & PaaS Tax          |               |               |              |              | $ (86.29)    | $ 78.94      |
| Vultr Expenses           |               |               |              |              | $ (40.00)    | $ (40.00)    |
| Total Infra Expenses     |               | $ (4,918.92)  | $ (2,049.16) | $ (1,459.07) | $ (1,564.53) | $ (1,276.75) |
|                          |               |               |              |              |              |              |
|                          |               |               |              |              |              |              |
| Recurring Services       | $ (183.65)    | $ (323.84)    | $ (389.75)   | $ (296.34)   | $ (585.68)   | $ (473.34)   |
| One Time Services        | $ (250.00)    | $ -           | $ (250.00)   | $ (300.00)   | $ (247.89)   | $ (275.07)   |
| Domain Renewal           |               |               |              |              |              | $ (98.65)    |
| Charitable Donations     | $ -           | $ -           | $ -          | $ (50.00)    | $ (1,000.00) | $ -          |
|                          |               |               |              |              |              |              |
| Totals                   |               |               |              |              |              |              |
| Total Income             | $ 7,917.00    | $ 14,177.00   | $ 9,510.00   | $ 7,675.00   | $ 6,016.00   | $ 5,131.00   |
| Total Expenses           | $ (4,420.58)  | $ (10,195.69) | $ (6,742.22) | $ (5,536.52) | $ (6,276.74) | $ (4,397.66) |
| Total Profit             | $ 3,496.42    | $ 3,981.31    | $ 2,767.78   | $ 2,138.48   | $ (260.74)   | $ 733.34     |
|                          |               |               |              |              |              |              |
| Stripe Balance           |               |               |              |              |              | $ 2,289.51   |
| Checking Balance         | $ 2,873.56    | $ 9,281.91    | $ 12,601.60  | $ 15,940.30  | $ 17,981.84  | $ 18,035.83  |

*The $275 One Time Services was an office chair for Luke. Migration away from AppSignal is in progress and should be ready early this month.*


### Team Reports
*Team reports now are aggregate summaries of the work being done on the Building Glimesh forum. Want to see your work here? Be sure to use our new forum!*

1.  Product Development Team
    1.  Support Button! We’ve renamed the Subscribe button to Support, so we can enable more ways of supporting your favorite streamers. Our first new addition is a way to link your Streamloots account directly to Glimesh so your viewers can use cards to interact with your stream.
    2.  [OAuth migration](https://build.glimesh.tv/t/oauth-migration/65) is scheduled to be rolled out on August 20th.
    3.  Mobile app testing should start shortly after August 20th.
2.  Design Team
    1.  [New site navigation design is being prototyped](https://build.glimesh.tv/t/visual-update-for-site-navigation/57).
3.  Community Team
    1.  New Community Team handbook is being developed & distributed.
    2.  6 new Community Team members are being brought on board to continue to engage with the community & be recognizable faces around the site.
4.  Marketing Team
    1.  [New marketing proposal](https://build.glimesh.tv/t/marketing-process-proposal/56) is being developed to figure out how to streamline work & future campaigns.
5.  Events Team
    1.  One community event scheduled for August 21st.
6.  Business Team
    1.  Working on a new [Contributor License Agreement](https://build.glimesh.tv/t/cla-for-contributions/54) for assigning ownership of assets.
    

### Previous Business
No previous business.


### New Business
No new business.
