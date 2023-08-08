---
title: Introduction to Cloud Computing
date: 2023-08-08 20:00:00 +0100
categories: [cloud-computing]
tags: [devops, docker, aws, gcp]
---

I struggled for several minutes to decide between two other topics for this post: **Why Cloud Computing?** and **What is Cloud Computing?**.

In the end, I settled for the above, because I feel it encompasses both, and provides a starting point for newbies to cloud computing.

Rather than give you some bookish definition to cloud computing, I will share a very recent experience with you.

## Why Cloud Computing?
My programming class received a lot of attention from prospects who wanted information, and it was becoming cumbersome to save contacts, respond to new leads, and provide information. To solve this problem, I decided to build a WhatsApp bot, and that I did!

Even though I *am* still working on the bot, it was already functional, and I was already using it to save a lot of time, and reduce the workload.

But then I turned off my PC for a while, went to sleep, and then came back to lots of unanswered messages!

What? 🤷🏽‍♂️

Then I remembered that the code that powered the bot lived on my PC, and shutting down my PC meant shutting down the terminal, from where I ran the NodeJS server!

That meant I needed to find a PC that would be powered, and connected to the internet, as long as I wanted it to.

A web host, right? I mean, that's something a traditional shared hosting plan would do?

Hold on a minute! I was constantly making changes to the code, and that meant that the code would change many times a day.
I could download the initial copy and reupload a copy each time I made a change, but that process, by my standards, is cumbersome, for when I could have at least 10 changes per day.

## What is Cloud Computing?
I promised not to give you a bookish definition, but you can read [this short article by Google](https://cloud.google.com/learn/what-is-cloud-hosting) for one.

Now that (I think) you have understood my plight, let us analyze what I'm looking for.

1. I need to purchase a new PC somewhere in the world (and most preferrably, power it with Linux OS).
2. I need to load my new PC with the code I wrote, and
3. I need to make it restart the server each time I made changes.

I will employ **Cloud Hosting** to cover the first two, and a **CI/CD** tool like *Travis CI* for the last one.
Also, I will be using *Docker* to create OS images, etc.

*...this post will be updated soon!*