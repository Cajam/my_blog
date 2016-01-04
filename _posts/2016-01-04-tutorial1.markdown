---
layout: post
title:  "Tutorial for the Past Me"
date:   2016-01-03 01:15:52 -0500
categories: tutorial
---
Anyone who has done even the shallowest of dives into programming understands how easy it is to get lost in your app development. While this is a wonderful feeling when you are tinkering on something hypothetical or a simple program, it becomes a problem when trying to complete a project. For those of us who eventually want to do this kind of work for a salary, the greatest restriction of all will come into the equation: time.

The biggest difference I've noticed between novice programmers and professionals is time management. At first, I thought you'd never have to reinvent the wheel when creating features for simple applications. While that's not untrue, finding reference material for coding (AKA, ravenous use of Google) is as much of a skill as writing programs itself. Focusing too much on trying to implement a feature that is hogging more than a few hours of your life usually results in this:

{% highlight ruby %}
git panic
{% endhighlight %}

If I could teach myself one lesson to take into Week 1 of General Assembly, it'd be to use the time management and planning skills that I already possess from my military career. We've learned about defining your minimum viable product features (MVPs), but I have found that adding an additional layer on top of that helps keep myself focused on the big picture by giving me backup plans for each of my MVPs.

The military teaches to implement something called a PACE plan with regards to establishing backup options. PACE stands for "Primary, Alternate, Contingency, Emergency." Applying this to programming is simple. For each feature of your application, write out your layered options, from a gold-standard down to your MVP.

Let's I wanted to write a nice calculator application:

<b>Primary:</b> You'd use your most reliable technique here. For me, that's using a prior code that is simple and works as a base to build off of. If I'm writing a calculator app, I'm going to look for another app that uses some JavaScript to do basic mathematical functions repetitively.

<b>Alternate:</b> This is Plan B. When it comes to programming, I've found that you should shift to this from your Primary course of action as soon as you feel like you're hitting a rut. It's OK to abandon Plan A pretty early on, that's why you wrote a whole PACE plan! The important thing about your Alternate is that it should be just as viable of an option as Plan A. For me, this usually involves finding some open source code on something like JSFiddle, Stack Overflow, or Github to take inspiration from on how to structure my code, or identify a solution to the same problem I'm having.

<b>Contingency:</b> Now you're starting to feel a little pressure. Maybe you're trying to write a program involving something you've never done before, or your Google skills are not revealing any answers that are making things easier to understand. The Contingency plan is the first one that I'd call a "backup." At this point, it's a good time to shut down your coding program, and review what your minimum viable product actually is. Try thinking of features you don't essentially need to have a working program, or go back to an earlier Git commit where your code wasn't throwing errors. At this point, I'd start wondering if my calculator app needs more complex features, such as memory retention of prior calculations.

<b>Emergency:</b> Time to panic. Just kidding, that's why you have an Emergency plan. This needs to not only be simple and adhere to your MVPs, but it also needs to be flexible and easily implemented. Personally, if you've gotten to this point and can't successfully achieve your MVPs, you are going to need some extra help. Fortunately for you, the programming world is incredibly open and supportive of each other. Ask questions or examples of "what right looks like" from your Slack channels, Stack Overflow, Reddit, your friends, co-workers, <a href="https://en.wikipedia.org/wiki/Rubber_duck_debugging">rubber duck</a>, or supervisor/mentor. Often times, you'll run into the answer in the middle of asking the question.

I hope that you've found a new technique to use in your timeboxing/planning process after reading this blog. Using the PACE technique has helped me improve my time management on projects by more clearing defining my MVPs.
