---
layout: post
title: "How to get better at software development?"
tags:
  - "development"
  - advice
  - faq
---

I often get a lot of queries from people asking me about how to get started with software development, and how to get better at it. My replies are almost reaching stock-level worthy of copy-paste now, so I thought I might as well write about it publicly.

What follows is a list of advice I'd give to any person who wants to write software for a living. A lot of it might apply across professions, and a lot of it is tailored to students in universtities. Not everything might apply in your case, YMMV. Take everything with a pinch of salt. Feedback is welcome.

1. ### Join a community. 
Highly preferable if its an IRL (In-real-life) community rather than just a chatroom somewhere, but even those are preferable over nothing. Communities have this shared sense of learning, that you don't enjoy anywhere else. Passive learning is something I talk a lot about, and it only happens because of chance interactions that happen in communities. Even online communities work fairly well, and by online communities I mean places like StackOverflow, AskUbuntu, ServerFault, HackerNews, subreddits etc.
If you don't have a physical community near you that you can join, maybe its time to start one?

1. ### Contribute to Open Source projects
It doesn't have to be with your code, or even a large project. Even small javascript npm modules that you might think can be improved deserve some Pull Request love.

1. ### Write all code publicly
Your code not being public should be the exception, not the norm. I've found putting almost all my code on github fairly liberating. I keep all my OS configuration and a lot of other things on github.

1. ### Do tech talks
It doesn't have to be at a big-name conference, but maybe at a small meetup around you. Good conferences will sponsor your tickets, and as a plus, you get to attend all the talks at that conference for free. Just make sure that you actually *do know* what you're talking about, unlike a lot of talks that happen.
The level of knowledge expected of a speaker is far more, and as a result if you are the one talking about something, you need to get better at it and understand it better, which is a great way of forcing yourself to learn something.

1. ### Stay Updated
Reading Hacker News is a fairly certain way of making sure of that. A person doing PHP development should be aware of things like Composer, HHVM, and perhaps the upcoming changes in PHP7 (They're awesome). As a technologist, part of our job is to stay updated with trends (no matter how insane the JS framework wars sound). The code you will be writing 5 years from now will be in an entirely different framework than what you are using today. This doesn't mean that you should start learning the ins and outs of every JS framework, but rather that you should be tangentially aware of developments happening in the space. (For eg, following stable updates of Rails even though you are not a Rails developer).

1. ### Learn more languages
I am a proud polyglot, and I very often realize that knowing more than one language changes your style and more importantly your thinking process significantly. For eg, a Ruby programmer will be fairly comfortable with the idea of metaprogramming compared to a PHP developer, and even more so when it might come to DSL (Domain Specific Languages). Similarly, knowing Haskell or Functional Programming in general teaches you a lot of things that you might re-use back in your JavaScript world.     
This doesn't happen unless you know more than one language. Moreoever, its always helpful to have JavaScript as your second language (if you are looking for one), because of its monopoly in front-end development. A lot of technologies (like CORS/JSONP) just don't make sense unless you understand JavaScript.

1. ### Concepts Matter
I was asking people about good interview questions, and one that I really liked was "How do you write an HTTP server using sockets?". A lot of developers are stuck in this moat of "programming = software development". And you can't get over that unless you start thinking in terms of concepts. This is not me trying to get people to become Architecture Astronauts, but me trying to get people to understand how things work.
I've interviewed people who have no idea about how HTTP works, and in my opinion you can't really be a web developer without knowing HTTP. A fairly good filter for good web developers is whether they know the ins-and-outs of HTTP. And HTTP is not a programming challenge, but rather a conceptual problem.
Similarly, if you work in the frontend, and you don't know what the Same Origin Policy is, I am not gonna hire you. ("Is it implemented on the browser or the server?" is a another good question). The point I'm trying to make is that you need to get a layer above your language's standard library and understand how things work. Learning ActiveRecord is awesome, but do you understand how it works?

1. ### Ship Products
Doesn't matter if they are small, or made in a hackathon. As long as its shipped, we're cool. If its not, come back when you've shipped it.

1. ### Have side projects
This is slightly harder to do, but far more rewarding. Make sure that your side-project is not something you *expect* to make money out of, and that it has a fairly reasonable scope. Side projects are an excellent breeding ground for you to try out new technologies, and play around with new languages. Its a really good breakaway from work-things as well, on top of that.

1. ### Read technical books
As a start, I'd recommend everything that codinghorror has suggested [here](https://blog.codinghorror.com/recommended-reading-for-developers/) and [here](https://blog.codinghorror.com/programmers-dont-read-books-but-you-should/). There are a lot of good books listed on hackershelf.com as well. My personal favorite is [Don't Make Me Think](http://www.amazon.com/exec/obidos/ASIN/0321965515), which is a book on Web Usability and something I think every developer and designer should be forced to read.


**Thanks** to [Shashank Mehta](https://shashankmehta.in) for discussing these ideas
with me and helping me frame this post.
