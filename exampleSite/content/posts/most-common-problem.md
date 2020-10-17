+++ 
date = "2016-03-10"
title = "5 Most Common Problems New Programmers Face"
slug = "most-common-problem-programmer"
description = ""
series = ["Getting Started", "Popular Posts"]
+++

![Most common problems new programmers face](https://miro.medium.com/max/1000/1*cD5EV6t2hepUqOVZwRiqwQ.jpeg)  

When you're just starting out with programming, it's easy to run into problems that make you wonder how anyone has ever managed to write a computer program. But the fact is, just about everyone else who's learned to code has had that experience and wondered the same thing, when they were starting out. I've helped teach several introductory programming classes, and there are some problems that trip up nearly every student--everything from getting started to dealing with program design.  

I'll prepare you to get past these challenges--none of them are insurmountable.  

#### Getting set up
Learning to program is hard enough, but it's easy to get tripped up before you even begin. First you need to chose a programming language (I recommend C++), then You need a [compiler](https://www.cprogramming.com/compilers.html) and a [programming tutorial](https://www.cprogramming.com/tutorial.html) that covers the language you chose and that works with the compiler that you set up. This is all very complicated, and all before you even start to get to the fun parts.

If you're still struggling with getting the initial setup, then check out our page [on setting up a compiler and development environment (Code::Blocks and MINGW)](https://www.cprogramming.com/code_blocks/) which walks you through setting up a compiler with a lot of screenshots, and gets you up to the point of having an actual running program.

#### Thinking Like a Programmer
Have you seen the State Farm commercials where the car wash company returns the cars to customers with the soap suds still on the car? The company washes the car, but it didn't rinse it. This is a perfect metaphor for computer programs. Computers, like that car wash company, are very very literal. They do exactly, and only, what you tell them to do; they do not understand implicit intentions. The level of detail required can be daunting at first because it requires thinking through every single step of the process, making sure that no steps are missing.  
![](https://youtu.be/QaTx1J7ZeLY)  

This can make programming seem to be a tough slog at first, but don't despair. Not everything must be specified--only what is not something the computer can already do. The header files and libraries that come with your compiler (for example, the iostream header file that allows you to interact with the user) provide a lot of pre-existing functionality. You can use websites like http://www.cppreference.com or our own [function reference](https://www.cprogramming.com/function.html) to find information on these pre-existing libraries of functionality. By using these, you can focus on precisely specifying only what is unique about your program. And even once you do that, you will begin to see patterns that can be turned into functions that wrap up a bunch of steps into a single function that you can call from everywhere. Suddenly complex problems will begin to look simple. It's the difference between:  


  Walk forward ten feet
  Move your hand to the wall
  Move your hand to the right until you hit an obstacle
  ...
  Press upward on indentation
    
and  

  Walk to door
  Find light switch
  Turn on light  



The magic thing about programming is that you can box up a complex behavior into a simple subroutine (often, into a [function](https://www.cprogramming.com/tutorial/lesson4.html)) that you can reuse. Sometimes it's hard to get the subroutine done up just right at first, but once you've got it, you no longer need to worry about it.  

You can go here to read more about [how to think about programming](https://www.cprogramming.com/tutorial/thinking.html), written for beginners.  

