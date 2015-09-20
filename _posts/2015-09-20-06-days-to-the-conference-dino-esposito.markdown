---
layout: post
date: 2015-09-20 10:00AM
title: "6 Days to the kick off: featured session of the day - Extending RWD with Lightweight Client-side Device Detection by Dino Esposito"
description: "Featured session of the day is Extending RWD with Lightweight Client-side Device Detection by Dino Esposito"
imagePath: /assets/2015/09/dino.jpg
comments: true
categories:
- News
tags:
- sessions
- agenda
---

Less than one week, and today we feature another session for just after lunch break: **Extending RWD with Lightweight Client-side Device Detection** and we asked [Dino Esposito](http://www.twitter.com/despos) to tell us more about his session and about himself.

Which session will you attend? This one on device detection with JavaScript, one about [software architecture with ASP.NET MVC](http://blog.webnextconf.eu/2015/09/18/08-days-to-the-conference-MVC-butland/) or about [performance and memory profiling on Azure](http://blog.webnextconf.eu/2015/09/16/10-days-to-the-conference-appinsight-maarten/)?

### Q: Tell us a bit more about your session
**A**: About a couple of years ago I asked a guru an opinion about device detection. He said you “Man, don’t need it. There are essentially two ways of doing mobile web development. One is building a bunch of pages that responsively work everywhere. The other is building two versions of the site, one of which is an m-site. The m-site is still responsive but designed for mobile devices and thus sending less content.”

I read the email quite a few times, then I went to the toilet, stood up for a while in front of the mirror and then I said it: “Man, this guru is an idiot!”
As I read it, the guru was trying to make the following points:

 - RWD allows you creating pages that can adapt to any screens.
 - RWD is so powerful that you can even use it to target mobile devices.
 - Who does or pushes device detection is taking you on the wrong path.
 - If you’re just willing to waste your time and money then feel free to set up a mobile-specific site, different from the primary one.
 - Mobile-first will save the world.
 -
About two years later I came to the same conclusion, but following a significantly different reasoning. Most of the time, all you need is RWD and a lightweight form of device detection that redirects to a mobile-specific site from the same URL. The one-site experience is preserved, the user is at the center of the universe, and mobile-first … is out of the way. Yes, you’ve got it right: mobile-first makes no sense and it is just a marketing slogan. Small-first is what it really means and it applies to implementation. Your planning of the site, and your architecture, should be instead device-friendly and target smartphones and smaller-screen devices differently from tablets. Even largest smartphones are too small to render appropriately the same content devised for an average desktop screen. RWD you say? At the end of the day, RWD is only good at hiding things once they’ve been downloaded (oh yes, 3G downloads do count!)

In this talk, you’ll get a perspective of devices that emphasizes the power of RWD for screens up to tablets and suggests device detection and m-sites for smartphones or, in general, for anything that screen-wise falls below a given breakpoint. There are numerous examples of companies and organizations that more or less silently are using optimized m-sites on some categories of devices. Device detection can be done on the client or on the server, with different benefits and costs. Nicely enough, everything discussed in the talk — the WURFL.JS framework — is available for free.

Finally, the talk offers the perspective of a youngster—one of those customers who just wish to have an app for everything and are able to throw any app away after two weeks. M-sites are quite different from native apps in terms of performance and experience. Even with Xamarin, though, you can’t always find the margin to build an app for everything. Not to mention that pushing an app takes a lot more than pushing updates to a web site. The question is, should we take a second look at Cordova?


### Q: Tell us a bit more about yourself
**A**: Author of many popular books that helped the professional growth of thousands of .NET developers, I've been speaking at events of any size for well over a decade. At present I'm a technical evangelist for JetBrains and member of the team that manages WURFL—the mobile backend tool used by Facebook.

## Register to the Web European Conference
If you want to attend this session but haven't registered to the [Web European Conference](http://webnextconf.eu/) yet, you still have some time: [go register](http://webnextconf.eventbrite.com/) before all 900 tickets are gone.
