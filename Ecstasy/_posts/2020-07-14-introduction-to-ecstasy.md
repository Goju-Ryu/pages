---
title:  "Introduction to Ecstasy"
---

## Welcome
This is the first entry in what is supposed to be a series of posts. The series will be about my experiences with the 
programming language _Ecstasy_ or _xtclang_. In this post I will provide a short description of the language, and its 
most notable features as well as a short summary of who I am and where I'm coming from. 

## Who am I
My name is Mads, I'm a software engineering student currently (2020) on my fifth semester. I primarily code 
in Java, though I'm familiar with c, Kotlin and python. I have also done some work in R and as a hobby I've 
been trying out Haskell. I recently discovered xtclang and was immediately intrigued. After having read every blogpost 
and seen every video about ecstasy that I could find, I thought it was about time to start trying it out for myself.  

## What is Ecstasy
Ecstasy is a programming language under construction. It is targeted at Java, C# and c++ programmers and is designed 
for the cloud. It is an OO language without primitives. Everything is an object, that includes ints, booleans, 
references and even null! 
Null is in fact an enum, making it no different from any other part of the language. If you are wondering how that can 
even be useful, the answer is union types. Ecstasy supports types to be defined as unions of types. This allows a 
function to return either some value of one type or another type. The most common use of this is to return a value 
or null.
The language has a strong focus on portability and security. This has lead to one of the more unusual aspects of 
Ecstasy. It has no access to the outside world without injecting resources in. this means that without the runtime 
injecting a console the language couldn't even print anything. This has the benefit of making the language completely 
environment agnostic and ensures complete control over which resources an application can use. 

To learn more go to the [xtclang blog](http://xtclang.blogspot.com).