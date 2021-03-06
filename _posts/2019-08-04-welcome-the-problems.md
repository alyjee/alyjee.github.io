---
layout: post
title:  "Welcome the Problems"
author:  "Tahir R."
image: /assets/images/welcome-the-problems.jpg
time: 1
categories: [software-engineering, tech]
tags: [problems, solutions, opensource]
---

As long as you facing problems in development be thankful and just keep looking for solutions. For quite sometime I've been thinking how these people, the tech gurus, are making such beautiful solutions and after a long time I came to know all these solutions are made due to the problems! Sounds crazy? Read along.

![apache kafka](/assets/images/welcome-the-problems.jpg)
Photo by Olav [Ahrens Røtne](https://unsplash.com/@olav_ahrens?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/search/photos/problem?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

As being a developer this is for sure that you'll face problems everyday during development. For example, you're using a github package and it does not support some functionality or what if you have to build a heavy i/o bound system and your tech stack is not able to support it. Now the question arises what you'll do?

There are two ways from here.
- You just solve your problem and move ahead.
- You make a solution so no other developer who faces this particular issue.

Let me tell you a short story behind all this. I was working on a project where I had to make concurrent requests to hundered of thousands urls and fetch data from them. Yes, we were making an ETL at that time. We were using Laravel queue jobs for further processings and insertions. The supervisord was the daemon, handling these multiple workers to fetch data from different sources. So during the development I faced a problem, from time to time we had to monitor the jobs and workers in supervisord, so what we'll do we log in to the server and check if things are working fine  or not, or sometime we monitro the jobs by quering the database. I was feeling that this is not right why we have to do all this over and over again and the process became overwhelming.

Now the question is what we did? Sadly, nothing! As our project was a success and everything went according to the plan so noone cared about this problem. No time later I saw this tool [Horizon](https://medium.com/@taylorotwell/introducing-laravel-horizon-4585f66e3e) which is made by the awesome dude [Taylor Otwell](https://github.com/taylorotwell) and he posted about it in this way.

So I think you got the idea, think about every problem as an opputunity to build sommething great for everyone and that's how you'll be contributing back to the community and trust we owe so much to these people.
