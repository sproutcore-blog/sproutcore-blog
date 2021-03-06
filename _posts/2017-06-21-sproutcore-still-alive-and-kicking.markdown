---
author: admin
comments: false
date: 2017-06-21 19:41:35+00:00
layout: post
link: http://blog.sproutcore.com/sproutcore-still-alive-and-kicking/
slug: sproutcore-still-alive-and-kicking
title: SproutCore still alive and kicking
wordpress_id: 2396
---

It has been quite a while since the last blog post. The reason for it is that there have been quite a few changes taking place since the last post.

The first news is that Tyler Keating has stepped down as project lead and has appointed Maurits Lamers to take over. From this spot we want to thank Tyler for the enormous amount of work he has done for the project and we wish him good luck.

Secondly we have been busy building new build tools using NodeJS instead of Ruby. The new build tools are simply called BT and are written in SproutCore. You can find more info on BT in the repository: https://github.com/sproutcore/build-tools. As the BT has had quite some time to mature, we are now dropping official support for the old Ruby based Abbot. The new BT offers quite a few advantages over Abbot:




  
  * **Development server is much faster**: The BT keeps and transforms all files in memory, speeding up a reload from 10s down to around 2s.

  
  * **Many different build types**: In abbot, it always was difficult to build SproutCore apps for different environments, such as Cordova. BT adds support for different types of bundling to match your specific wishes.

  
  * **ES5 strict compatible**: Abbot only supported SproutCore builds in ES5 non-strict mode. BT allows your SproutCore app to be fully ES5 strict compatible, and also offers support for ES6 through Traceur.

  
  * **Written in SproutCore**: BT is written in SproutCore, so as a developer familiar to SproutCore, it is much easier to contribute.



Thirdly the community has lost a few active core team members who were hired away. We want to thank them for their contributions. Sadly, the downside is that it has left a few projects such as documentation updates that were underway without active support. As such we are very much welcoming contributers of any kind!

Thank you for your patience and continuing support!
