---
layout: post
title:  "A Rails Girls experiment: Nitrous.io and Reveal.js"
date:   2014-08-11 23:22:10
categories: events
---

#A Rails Girls experiment: [Nitrous.io](https://nitrous.io) and Reveal.js

Before running our Rails Girls event, our organising team were extremely lucky to experience Rails Girls events first-hand. Nat attended Rails Girls Wellington 2013 as a student, and both she and Maria helped out at the Wellington 2014 event.

We learned a lot from the amazing job the Wellington team did. This meant when it came to our event, we were able to try something a little different.

![railsgirls auckland intro](https://raw.githubusercontent.com/natdudley/railsgirlsblog/master/images/rgakl.jpg)

##Background

Typically, a Rails Girls event starts with an installation party. Our students few hours of their time with us installing a text editor and a local installation of Rails. With Rails Girls events being short on time, this takes up valuable hours that could be spent learning.

Recently, the cloud technology field has expanded to include software development IDEs. These tools enable developers to skip the set-up and get straight to coding. They provide many things a developer needs, and all in the browser. This includes command line and the ability to store your code on GitHub.

These tools enabled us to try running our Rails Girls event a little differently; we could skip the installation time altogether, and instead, spend that time providing a more thorough introduction to coding, with more talks and more time to spend in workshops.

![railsgirls auckland intro](https://raw.githubusercontent.com/natdudley/railsgirlsblog/master/images/rg1.jpg)

In addition to this, Rails Girls events typically run using the standard training material on the railsgirls.com website. The Rails Girls team worldwide have done a great job creating material that allows anyone to pick it up and run an event anywhere in the world, however, it relies on the coaches spending a lot of time explaining concepts.

For many students, asking for more explanations is intimidating, especially on top of trying to learn to code for the first time. This meant that some students were just following the directions, but not understanding what they were doing.

##What did we do?

For our event, we tried three things:

1. Using [Nitrous.io](https://nitrous.io), one of the pioneers in the Cloud IDE space. It's a freemium tool (you can create one app at a time for free).
2. Integrating the explanations from the coaches guide (and other great Rails resources around the web) into the student training material, so all students got explanations as they learned.
3. Formatting the code as an online presentation, using Reveal.js. This allowed students to focus on a single step at a time, and scroll down for more explanations if they were needed.

###Benefits of using Nitrous.io

![railsgirls auckland intro](https://raw.githubusercontent.com/natdudley/railsgirlsblog/master/images/rg2.jpg)

####Attendee diversity

Using Nitrous.io gave us several advantages. Firstly, we could accept students who used Chromebooks or Netbooks, or who only had school or work laptops where they could not install Rails locally. 

We were also able to accept students who had no laptop, and arrange loan laptops for them. Because Nitrous.io is all in the cloud, these students could go home and continue to build their app on their desktop computer just by logging in.

####Extra content

Usually, in a 1.5 day Rails Girls workshop, there's simply not enough hours to get through everything you want to do. We were able to add in a great talk from one of our coaches introducing students to programming basics (it even included demonstrations of loops and arrays using animated bunny rabbits!) We also had time to run streamed workshops to finish the event: a front-end workshop and an advanced Ruby workshop, which allowed our students to explore more aspects of coding.

![railsgirls auckland intro](https://raw.githubusercontent.com/natdudley/railsgirlsblog/master/images/rg3.jpg)

####More welcoming and fun!

For most of us, setting up a local dev environment is tedious at best. For someone new to coding, it's a terrible first impression. We get them all excited about learning to make amazing things...and then we get them to spend hours installing the tools to let them do it. Using Nitrous.io removed this entirely. Our students kicked of with the programming basics talk, and then, as teams, learned to program a "robot" (their coach) through a maze to get_cupcake. Our students left the first afternoon enthusiastic and excited, and with some solid programming basics under their belt. 

![railsgirls auckland intro](https://raw.githubusercontent.com/natdudley/railsgirlsblog/master/images/rg4.jpg)

##How did it go?

The proof of the pudding is in the cooking; it's all very well to try something out, but did it work out?

The feedback we received from students was overwhelmingly positive. They loved being able to dive right in and start learning straight away. An added benefit was the inbuilt previewing provided the students with a URL they could share with family and friends as they learned. Their friends and families could follow along at home, and see what our students were building.

Positives:

- Saved time
- More user-friendly and welcoming
- Easy steps to authorise GitHub access
- Easier for coaches (no failed installations to troubleshoot!)
- IDE came with some Gems pre-installed. This meant students didn't need to worry about installing Brew, ImageMagick, and other common gems.
- No need to deploy to Heroku or another 3rd party service
- Students can see everything in one place - their code, their terminal, and their project structure were all in one browser tab.

Negatives:

- 50 students trying to connect their GitHub account to their Nitrous account via the API resulted in some rate-limiting (and subsequent failures). Coaches were on hand to troubleshoot this, but it made it a bit more complicated.
- Coaches less familiar with the in-browser development style
- Our front-end workshop involved a lot of CSS changes. Nitrous caches CSS, which meant students needed to take extra steps to clear the cache when they updated CSS.

![railsgirls auckland intro](https://raw.githubusercontent.com/natdudley/railsgirlsblog/master/images/rg5.jpg)

###Would we do it again?

Absolutely. The extra time to learn and the more user-friendly introduction was invaluable. We'd probably ask students to set up both their Nitrous.io account and their GitHub account before the workshop, so the issue with linking the two was avoided.

The caching issue was the only real drawback. If not fixed, we'd simply update the instructions to explain how to clear cache.

###What do you need to know if you're considering trying this out?

If you're a Rails Girls organiser, and you'd like to try running your Rails Girls event this way, there are some steps in the Rails Girls material that need to be altered slightly. Our [amended training guide is available here](https://github.com/RailsGirlsAuckland/Rails-Girls-Training).