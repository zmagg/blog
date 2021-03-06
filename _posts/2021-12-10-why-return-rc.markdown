---
layout: post
title: "Why return to RC? (and some notes on what I spent week 3 & 4 at RC doing)"
date: 2021-12-09 21:16:00 -0500
---

### Why return to Recurse Center?

I'm writing y'all from North Carolina where I'm visiting friends and family. Coming back here always makes me think of the phrase "You can't go home again", after the Thomas Wolfe novel set here. For me as a programmer, Recurse Center has been my home since I was last in batch in 2013. I came in as a young programmer who had worked in the tech industry but wasn't sure if the tech industry was the right place for them and I left feeling like I should at least give it more of a try.

Although the Thomas Wolfe novel is maybe not culturally relevant still, many family, friends, and strangers asked me why I was going back to do something I had done before.

I wasn't super sure myself when starting to be honest. Some of it was motivated by wanting some structure around my day to day life immediately after leaving the rigid structure of a day to day corporate job, as well as wanting to be around other people going through a similar experience and time in their life. All of this has been FANTASTIC, which I've shared in prior posts. Some of  my motivation was also emotional though. I'm working through what it looks like to keep going in the tech industry and this is where I first found the space to really give it a go.

One thing that's surprised me has been the permission to be a beginner again as well as the energy that comes from being around other people who are also doing something new !! to them. I spent the first two weeks building astronomically accurate sun art in Typescript, none of which I knew how to do before getting started. (( Sidenote: still have to finish this project. )) Great teams and workplaces can give space for even experts to ask beginner style questions, but for the most part for the last few years I've been in roles where I've been expected to ramp up fast and lead from what I've seen before. It's been a real joy to get to just do stuff I really don't know how to do. In the context of RC it's also been fun to see how much faster I am at problem solving than I was 8 years ago when I was last here.

### (Attempting to) teach from what you know

A few weeks ago I asked [on twitter](https://twitter.com/zmagg/status/1461450620628451328) how people who had worked in the industry for 15+ years kept it feeling exciting and new. A lot of people said teaching and mentoring.

Fortuitously for me as I navigate trying to continue in this industry, I got the opportunity to do some more structured teaching recently. My friend Lindsey Kuper asked if I'd give a guest lecture for her undergrad distributed systems class at UC Santa Cruz, so I spent week 3 at RC prepping a talk for this class. This is the kind of teaching that I've always found most challenging--teaching to an audience where you have a BIG experience gap. I've always found it easier to teach people something I've just learned, or to teach people who have worked on similar systems and just need to know the specific details that differ. The talk was pretty well received though, and it seemed like the undergrads were engaged and following the material for the first 90% of the talk, which is great.

[Slides](https://docs.google.com/presentation/d/1FBoSJzwLbG4f9otW8Ki3nj84BesKyr-dnam0EApEFxA/edit?usp=sharing) are here, and I'll be giving it again at Recurse Center in January, where I will maybe record it. Content is some old systems design decisions Slack made, as well as two old incidents we had around the distributed database I worked on there. Side note: I hope that the content is old enough that Slack is cool with me talking about it externally, but uh, if you (still) work at Slack and you're reading this and you think I should've checked with someone, let me know?

In prepping for the talk, I chose the incidents to highlight some things related to what was in the course curriculum--namely replication, sharding, and consensus. One thing I would've wanted to know more about as an undergrad in a class-like setting is how these decisions actually show up in the real world. Something that I've learned while working is that although some systems design decisions are made at the whiteboard level weighing tradeoffs ahead of time, others you only find out about after you run your system and hit an incident. And then you get to make a decision about just how much time you're willing to invest in fixing the problem you've created, and that can dictate as much of the solution space as anything else.

Ok, those are just my feelings about this talk. I'll attempt to post a lightly edited transcript version of the talk to this blog soon so that people who don't like watching videos (like me) can get something out of the material too.
