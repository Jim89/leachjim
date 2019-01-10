---
title: Do the simple thing first
author: Jim Leach
date: '2019-01-10'
slug: do-the-simple-thing-first
categories:
  - Data Science
tags: []
description: "Before jumping to complex and sophisticated approaches, try something simple. The results might surprise you"
draft: yes
---
   
This will be a short post outlining my thoughts on trying different approaches
to solving problems (mainly in the context of data analysis, but the ideas might
extend beyond that). My main conclusion is this: always try the simplest thing
you can think of first.

Imagine the situation: you're starting a new project and you've been assigned a
goal, predict which product(s) to recommend to a customer when they come in to
your shop/visit your website. Adding some detail, imagine that you work for a
company that sells day to day essentials, food, etc. (i.e. a supermarket). You
track what customers have bought in the past (maybe through an app they use if
they're in the shop) and those data are available to you. 

Sounds exciting, right? it's going to be like Netflix - you can look at what
people have bought, try and find similar people (based on _their_ purchase
history), and recommend products that way. You'll be just like Netflix (only
you'll recommend different brands of milk rather than [genre-bending interactive
media experiences](https://www.netflix.com/title/80988062)). But wait, have you
tried the most simple thing you can do first? To (mis)use an IT support phrase -
have you turned it off and on again?

![off](https://media.giphy.com/media/DUtVdGeIU8lmo/giphy.gif)

What might that simple thing be, though? Well, here are a few very simple ideas:

1. Count all sales, and find your number one product across all customers;
recommend that to everyone.
1. Find out each customer's most bought product; recommend that to them.
1. Combine the first two approaches, so all customers get both a general and a
personal recommendation.

But surely this won't work? It'll be too broad, and the recommendations will be
useless! That may be the case, but you need to _test_ that before you move on to
more complicated methods. Of course you'll need a reasonable framework to
evaluate the success of your simple method (which is outside the scope of this
post), but you should test and evaluate it nevertheless.

Until you've tried you don't _know_ that it won't work. It might actually turn
out to work quite well (in this example, it would probably do "ok" for some,
frequently bought, items); maybe you can save yourself the time and effort doing
something more complicated. And that's what trying simple things first lets you
do: justify the cost of something more complicated once you know that the
simple answer isn't the right one.

That last point is really my main conclusion and motivation for this post. __A
complex method is never justified until a simple one has been tried first.__ In
our example, yes, you _could_ build a much more complex recommendation system,
but unless you'd tried and evaluated some sort of "count and rank" method, maybe
a frequency analysis (e.g. how often does a customer purchase vs. when did they
last purchase), or a simple-ish market basket analysis (i.e. association rule
learning) I don't think I'd be sold on a more complex method being the best
answer. And I certainly wouldn't be convinced that the time and/or money you
spent developing it was justified without seeing some results that showed a
simpler method just didn't cut it.

Try something simple first, it might work, and if it doesn't you've at least got
a reason to try something more sophisticated for round two.