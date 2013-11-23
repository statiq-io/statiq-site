---
layout: post
title: A detailed rant&#58; Why mobile web apps are slow
date: 2013-08-05 10:13:00
author: Joshua Howland
type: Link
link: http://sealedabstract.com/rants/why-mobile-web-apps-are-slow/
categories: Development Native Web
slug: a-detailed-rant-why-mobile-web-apps-are-slow
---

It's a long read, but a great one. I love this portion of the article most: 

>One of the problems with these “X is slow” vs “X is not slow” articles is that nobody ever really states what their frame of reference is.  If you’re a web developer, “slow” means something different than if you’re a high-performance cluster developer, means something different if you’re an embedded developer, etc.  Now that we’ve been through the trenches and done the benchmarks, I can give you **three frames of reference** that are both **useful** and **approximately correct**.

He compares the iPhone app experience: IE8 for Javascript developers, 50x slower for C++ developers, and 10x slower for Ruby, Python and Java developers (but only if your program fits in 35MB).

It's really interesting that we're still talking about this. When I've interviewed with startups, I've consistently been surprised that they've asked me about this: "can we do a mobile web app version and be done?"

The short answer 99.9% of the time is: **NO**.

This article covers in depth why web apps are so much slower than native apps. And (as he hammers throughout the article) it's not anecdotal evidence; it's quantifiable evidence.