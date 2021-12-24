---
layout: post
title: A compiler with soon in the process baked in hashing function and also a distributed
  git
date: 2019-07-08 20:57 +0200
---
Ok, you start with writing a compiler from the ground up and bootstrapping it in every step, as soon as you're able to make a hashing function you hash every preceeding step the way git does it. Now you have a git at your disposal. The next step is to make this git distributed, which means that when you add source code, you can hash it and distribute the source code over peers, peers who can hash too and compare the hashes. It's almost certain that if there's been tampered with the source code in the whole process, a malicious can be identified and excluded.  
Create source code, hash, distribute, compare hashes, continue/block.  
This way malicious hacking is prevented, even if the hardware has been adapted, because the earliest commits of the compiler will be the same and the next commits will be controllable and comparable.  
It should be an ever controling mechanism, not sitting still.  
