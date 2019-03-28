---
layout: post
title: A compiler with hash function for hashing the whole development process
date: 2019-03-28 11:25 +0100
---
A compiler should be made where there's a built in hash function early in the bootstrap process of the compiler - see bcompiler on github as an example to bootstrap.  
The goal is to create a simple language like c, but with a hash function.  
Another goal is to be able to verify every step in the development process of the code and be able to compare development with production as to block hijacking of code somewhere in the whole development process.  
Git's hash function is not early enough and isn't as secure as I like it to be, that's not git's purpose.