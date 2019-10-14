---
title: "Daily Blog: 10/13/19"
date: "2019-10-12T22:40"
tags: ["daily-blog"]
---

*Hi everyone, welcome to my daily blog series! This series is where I write something, anything, daily about my journey in tech. If you enjoyed this post, check out other posts in the series [here]()*

While flying from Phoneix to Boston on a work trip I loaded up on a bunch of episodes of the [Bike Shed](https://bikeshed.fm/) podcast by Thoughtbot to pass some of the time. It has been a while since I've listened to the show regularly, mostly because my commute is now only consists of walking down the hall, and I was excited to catch up on some of the content I've been missing.

I often find myeslf disagreeing with some of the points in the show and that's what keeps me coming back (different ideas are a good thing!). An instance of disagreement during one of the episodes inspired me to write this post! The specific topic involved for this is around staticly typed vs dynamically typed languages and how they effect productivity. 

I'm paraphrasing here but the prevailing idea was that static type systems like those found in Elm or Rust slow down developers and make it harder to jump into working on a project. That dynamiclly typed programming languages let developers get started faster building a prototype that can be worked on to be improved later.

While I think it's a solid argument in favor of dynamiclly typed languages it misses some of the forest for the trees about the trade off between static and dynamic types. When a language has a sufficently strong type system it works in much the same way that writing unit tests do in a TDD environment. The types (and unit tests in this example) point you as the developer in the direction to head. Understanding how to model the problem being solved for via a type system encourages deeper thought about the environment as a whole and leads to a more robust solution out of the gate. Conceptually working through the problem moves the development progress along even without having code to show for it and makes the code that is eventually written of a higher quality. Going this route doesn't mean you're moving slower but just that you're moving differently.

What do you think about the place of strong static type systems in the programming world? Do you find it helpful to model problems via the type system or do you prefer to just jump into writing code and work on the typing structure later?
Let me know on [Twitter](twitter.com/mstallmo)!

Also if you haven't listened to the Bike Shed yet check them out on your favorite podcast app!