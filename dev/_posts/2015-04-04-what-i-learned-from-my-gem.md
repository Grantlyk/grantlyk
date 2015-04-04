---
layout: post
title:  "What I Learned From My Gem"
date:   2015-04-04 14:56:00
tags: featured
image: /assets/article_images/2014-09-29-welcome-to-my-blog/article1.jpg
published: true
---

# What I Learned From My Gem

## Introducing Sink Utility
Meet [Sink_utility](https://github.com/Grantlyk/Sink_utility "Sink_utility - The repo Syncing CLI"), The CLI for sycning remote repositories together, The idea behind Sink is that it's simple and faster than the current means, it's like turning the cart into the car.

## Why?
When Github got DDoS'd recently it opened my eyes to the thought, if one of the main repository hosting websites goes down, lots of people would loose money as lots of companies use these services as a vital part of their development strategy. So I made a back up service. Download the gem, run the `sink setup` and then run `sink all` and that's it! It's a quick way to back up your github/bitbucket repo to bitbucket/github if something is happening to the one of them or if you just want to be safe.

## It Isn't Rocket Science
It really isn't, Sink is a really simple gem that I created mainly for some practice and the experience of writing gems. I'll let you in on something that's no secret, as it currently stands it's basically just several git commands executed via one command, it's as simple as an alias. Throw in some puts, gets & case statements and you're there. It's incredibly easy to start a gem, so why not?

## Why Am I Telling You This?
Because it's super easy to write a gem so if you haven't I suggest you do it.

###Three Reasons
1. It helps you learn about how gems work
2. It gives you something to work on later 
3. You can add it to your github portfolio (anything that looks good to employers generally is good)

## But What Did I Actually Learn?
###I Learned
- [Semantic Versioning](http://semver.org/)
- How to create a Gem
- How to publish a Gem
- How to Persist data in a gem
- Why your gem must be Robust
- How to prepare for users


