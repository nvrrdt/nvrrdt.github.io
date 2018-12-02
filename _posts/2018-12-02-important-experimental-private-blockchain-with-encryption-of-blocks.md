---
layout: post
title: IMPORTANT Experimental private blockchain with encryption of blocks
date: 2018-12-02 19:43 +0100
---
Why not encrypt a block? (instead of hashing)

Filename of the block is 'blockheight + public key of previous block'.

In the block are transactions.  
Every payer or payee should get a public key.  
Through some work/stake the payers and payee should settle for a private key.

Storage of only the blocks where you got the private key + the next block for the public key.

Every block has it's private key stored at the payers/payees of that block.

Encrypting a block should include the filename in order to create a chain.

This is just a thought that doesn't work. It should be impossible to download the whole chain with the public keys included, so this is a flaw.  
Or when you have the private key, it's a public key he ... maybe it could work. I need to work on this.  
So you need to store your private keys like crazy.