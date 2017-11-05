---
layout: post
title: Q&A with Nada Amin
date: 2017-11-05 13:00:00
tags: 

excerpt: Q&A with University of Cambridge Lecturer Nada Amin, who is speaking at the the Code Mesh conference in London this week.

author:
  name: Katie Ots
  twitter: codemiller 
  gplus: KatieMillerCodemiller 
  bio: Lambda Ladies Co-Founder
  image: katie.jpg

---

Q&A with [Nada Amin](https://twitter.com/nadamin), [who is speaking](http://www.codemesh.io/codemesh2017/nada-amin) at the [Code Mesh](http://www.codemesh.io/codemesh2017) conference in London this week.

Nada is a lecturer at the Computer Laboratory at the University of Cambridge. Previously, she was a member of the Scala team at EPFL. She has contributed to Clojure’s core.logic and Google’s Closure compiler.

<img src="/images/nada-amin.jpeg" style="width:250px;display:block;margin:auto;" alt="Nada Amin"/>

### What are you speaking about at Code Mesh, and what are some of the audience takeaways from your talk?

I am speaking about collapsing towers of interpreters. The takeaways are:
(1) there are principled ways of turning interpreters into compilers
(2) they can be used to turn a slow tower of interpreters into a one-pass compiler that removes all interpretive overhead
(3) they even apply to reflective towers of interpreters, where the user can jump up and down levels and where the number of levels is conceptually infinite.

### How did you get into functional programming? What do you enjoy about it?

I got into functional programming by reading Structure and Interpretation of Computer Programs (SICP) in high school.

I like having the feeling that I can reason through my code before or even without running it.

### What are you working on at Cambridge at the moment?

I am still defining my research agenda. I've been working still on collapsing towers, and trying to better understand them in theory and better exploit them in practice. In particular, I'd like to apply the technique to collapsing towers from Scheme to miniKanren to (relational) Scheme.

I've also been looking at neuro-symbolic reasoning, and my goal would be to be able to go back and forth between symbolic and neural
representations of a program, so that a program can be partially learned from data. As an example, one could have a domain-specific
language for harmonizing, and then learn how to harmonize from a corpus of Bach chorales and then extract actual symbolic rules from
the learning.
  
And there are many more such things, old and new, that I'd like to explore.

### Some functional languages/concepts are challenging. What techniques do you use to teach functional programming, and encourage students to persist with it?

I try to give students fun exercises.

In terms of techniques, I like to help them derive concepts for themselves: for example, fold can be extracted from working out structural recursion on a few examples.

Types can also be helpful as a starting point to write a function, and also as an ending point to understand it.

### Why do you think there are so few women in functional programming compared with other areas of software engineering, and do you have thoughts on what we can do about it?

I didn't realize that it was better in other areas of software engineering...

