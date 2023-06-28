---
title: "Great, another OSWE blog"
date: 2022-06-20T22:23:51-05:00
description: My thoughts on the OSWE exam
slug: oswe
hideReadMore: true
---

It's been quite a while since my last post. I was busy with finishing up my degree and trying to get my foot in the door to cyber security.

At this point, if you're preparing for OSWE you've probably read through tones of blogs already. With this blog I've tried to keep it short and simple. I'll outline my approach towards cracking the exam and try to answer common questions I get, so that I can shamelessly direct anyone asking here.

`Background`

Prior to preparing for OSWE I had zero experience in code review and while I don't have any professional experience in development, I can quickly hack something up in PHP, Python or NodeJS if needed.

I'm not OSCP certified, and I didn't touch HTB for preparation.

I registered for the two-month course and took 300 hours over a span of 3 months, from pre-registration to taking the exam and passing on the first attempt.

`Pre-Registration`

- Be comfortable with common web vulnerabilities & Burp Suite. The course is focused on web applications.
- Know at least one languauge (preferably Python). You'll have to fully automate exploits to pass.
- Have a basic understanding of MVC & OOP concepts. You don't want to end up looking at an interface or abstract class and wonder why all the methods are empty.
- Knowing your way around regex will help a lot, but you can pick this up as you go through the course, if you aren't familiar.

The amount of content available online is somewhat overwhelming. I'd narrowed down resources and skimmed over topics that I was already familiar with. Paired with the course material they provide excellent coverage:

- [z-r0crypt's Blog](https://z-r0crypt.github.io/blog/2020/01/22/oswe/awae-preparation/)
- [Wetw0rk's Reources](https://github.com/wetw0rk/AWAE-PREP)
- [21y4d's Post](https://forum.hackthebox.com/t/oswe-exam-review-2020-notes-gifts-inside/2232)
- [Nathan Rague's post](https://hub.schellman.com/blog/oswe-review-and-exam-preparation-guide)

These blogs have great writeups with varying degrees of complexity:

- [Code White Sec](https://codewhitesec.blogspot.com/)
- [Assetnote](https://blog.assetnote.io/)
- [Sonar Source](https://www.sonarsource.com/blog/)


`Post Registration`

For each application in the lab, I followed a simple strategy, spending a minimum of 30-45 minutes on each step even if I wasn't able to progress:

1. Find out how request routing works in the application without referring to the material, regardless of whether it's covered or not. This includes being able to trace a function back to its route and vice versa.
2. Trying to find the vulnerability on my own once I feel that I have enough background knowledge on the vulnerability being covered.
3. Writing exploit scripts referring to the course material.

This really helped me in fleshing out a concrete methodology that I could use when I actually have to do a code review for fun, in a project or in the exam.

With my lab time running out I didn't complete all the extra miles but was able to solve the majority of them. Instead, I wanted to focus on getting one mock exam done and selected two extra machines whose solutions aren't provided. I gave myself 48 hours and skipped reporting. This was important to test my methodology and refine it further for the actual exam. I found the exam boxes to be a bit trickier, but still doable.

`The Exam`

Being able to cover the extra miles will be really helpful in passing the exam and I'd suggest doing as many as possible on your own.
 
 - Keep any scripts you've written during the duration of the course handy to save time during the exam.
 - Take frequent breaks. I paced in my room for a few minutes after every hour and a half. Code review can be mentally taxing if you're new to it.
 - Make sure that you get a good amount of sleep. I ended up finding the last vulnerability too late because of a simple mistake I made when crafting payloads since I'd slept for 3 hours on the second day. Fortunately, I had enough points to pass at this point.
 - Make sure you take screenshots of everything!

`Closing thoughts`

While the course material is excellent, I needed some additional reading from online sources to get comfortable with some of the more complex topics. Anyone who's interested in getting started with secure code review will find this as a really good starting point, and you'll feel comfortable reviewing code in languages you may not be able to code in.