---
layout: post
title: Interview with Chris Martens, Programming Languages Ph.D Candidate
date:   2014-09-02 08:37:19
tags: logic programming, games, celf, profile

excerpt: Learn more about Chris Martens's work on logic programming, games, and forging new connections in computational creativity.

author:
  name: Kelsey Gilmore-Innis
  twitter: kelseyinnis 
  bio: Lambda Ladies Co-Founder
  image: kelsey.jpg

---

Learn more about Chris Martens's work on logic programming, games, and forging new connections in computational creativity.

###Who are you and what do you do? 

I'm [Chris Martens](http://www.cs.cmu.edu/~cmartens/), or chrisamaphone everywhere on the internet, and for the last ~6 years i've been a computer science grad student at CMU!

###Tell us about what you're studying.

I've been studying in the [POP (Principles of Programming)](http://www.cs.cmu.edu/Groups/pop/pop.html) group. We're all working on programming languages in some capacity, usually with a types/logic angle. I've done a couple of projects on dependent types and proof assistants, and now I'm working on a logic programming language for my thesis.

###What's logic programming?

Logic programming is a way of interpreting a collection of logical assertions as a program! In the wild you might encounter Prolog or (more practically) database systems like SQL -- the concept of a "query" comes from the idea of asking a question in logic, "is the formula A provable," and then having your program execute as a search for a proof of A (there might be multiple proofs.) At its core, a logic program interpreter is "just" a theorem prover.

###What kind of problems would you say logic programming languages are well suited for?

I'd say any time you're thinking primarily about the *relationships* between data, logic programming might be a good fit. I think their most common use is in databases, but that's actually the one I'm least familiar with. I've used logic programming most as a tool for expressing formal systems -- things like languages and logics that you can describe naturally through inference rules. 

###Systems like...say, games?

Heh. Yes! I was trying to figure out a good segue to that...my thesis project started with noticing that logic programs might be a good way to represent the rules of games. Games aren't always thought of as formal systems, and some argue that doing so can impede design. But on the other hand, I like to think of a formal description as something that sits nicely at the boundary between human and computer. As a human, you can think more in terms of game rules instead of "how exactly am I going to represent all these data structures and get good performance", but you still have something you can execute & play with.

###Is your thesis language specifically related to games?

Yep! I started out trying to make it really broad and talk about "interactive systems" in general, but having a really specific application has helped me make a lot more progress...especially an application that I care about independently from PL stuff, and one that a lot of people can relate to and talk about.


###Tell us a little bit about the language itself and in what ways games/interactive systems have shaped it.

The language I'm starting with is one that I got super into after my advisor Frank Pfenning, who coauthored the language, taught a class that used it. It's called Celf, and it still lives in a tiny little academic corner with zero documentation, but you can find it [on GitHub](https://github.com/clf/celf). My language will basically be talking Celf, skimming off a simple subset of the language, and adding capacity for interactive execution, along with some special mechanisms for control flow between program components. My design has also been inspired by [Inform 7](http://inform7.com/), a popular engine for making text games. It's basically a logic programming language already... but as I've used it I've been more convinced I need to make a language based on Celf!

###OK, so at this point I have questions about PL design and also about games...walk north for PL design, and open the door for games?

&gt; open door

###Tell us about a game you've made!

So, I mostly make interactive fiction (IF), except my IF is weird because I don't really like writing fiction -- I tend to just make these weird little systems that happen to get rendered in text. But recently I've been into a 2D games engine called [LÖVE2D](http://love2d.org/), which I used to make a game called "QWOP training run"
and it kind of has the structure of IF, in that i'm telling a branching story (autobiographical) through it, but it's superficially just an arcade-like running game (you mash keys to run faster.) The branching points in the story are represented by geographical branching points in the running route. You can [check it out yourself](https://drive.google.com/folderview?id=0B1HJXoh3BOUbU21LcWZiWGVyZ0E&usp=drive_web).

###Are you a gamer? What draws you to game design?

I dunno if I'm a gamer. I feel like there's a lot of gatekeeping around that term, so I prefer to stay away from it. But I really enjoy what people who approach games as an artform can manage to do with it. It's a form of expression where your audience participates in the experience, so you can use that to tell stories, or to communicate systems, including social ones. A lot of what I like about games is the same as what I like about math. It's stuff you express in rules, and the rules *do* things - they contain this world that (if designed well) will keep surprising you.

###Do you have a strong math background?

No and yes. I don't have a lot of what I think of as "standard math" -- calculus, real analysis, linear algebra... but I've learned a lot of algebra and category theory over the last few years, which is pretty fun. I was lucky enough to be at CMU where Steve Awodey was teaching category theory, sort of at the forefront of a new wave of mathematical foundations, a few years before the Haskell community exploded and everyone was talking about it.

###Speaking of! Do you consider yourself part of any computing "communities"?

Community is tricky for me (maybe just as tricky as for everyone). It seems like academics are expected to find community w/their collaborators & colleagues, but it never felt easy for me to fit into that. And a lot of non-academic groups tend to focus on one specific language, which also doesn't feel right to me. So that leaves online communities, and I guess the sort of ad-hoc computing communities that form on [Twitter](https://twitter.com/chrisamaphone) are the ones I feel most active on. People say Twitter is no good for discussion, but I've had some pretty constructive academic & programming discussions on there.

###Thoughts/feelings about academia vs games programming you do?

Academic CS and the kinds of games communities I follow seem like they're about as far apart on the "tech" spectrum as they can get. Within games communities, "academia" often refers to humanities or arts programs -- or maybe this is just my IF predisposition, 'cause a lot of those folks come from "electronic literature." And when they think of computer science's relevance to games it's usually "AI," for various values of things under that umbrella (conversation bots, NLP, social modeling) rather than programming languages (PL). I'm hoping my research will take me in directions -- either by doing more academia or getting hired by more experimental games companies -- that can bridge the ideas. I think PL, functional programming, etc. have a lot to offer digital arts & computational creativity, because we think a lot about *interfaces* to expression. The cultures are just so different. I wanna help that change!

