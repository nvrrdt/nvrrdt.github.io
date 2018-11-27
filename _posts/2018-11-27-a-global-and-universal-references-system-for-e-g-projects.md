---
layout: post
title: A global and universal references system for e.g. projects
date: 2018-11-27 21:39 +0100
---
First the study agency:
<study agency reference[e.g. 32 bit hash]><project reference[e.g. 64 bit hash]><contact reference[e.g. 64 bit hash]><revision number[e.g. 16 bit sequential]>
Then the installer:
study agency cypher + <installer reference[...]><contact reference[...]>
Then the sales office:
previous cypher + <seller reference [...]><contact reference[...]><quotation reference[...]><revision number[...]>
Then the factory hash:
total sales office cypher + <factory reference[...]><contact reference[...]><product reference[...]><revision number[...]>
+Transport...
+Installer...
+...
Maybe including a cypher version number to enable more possible versions of the cypher simultaniously. Or make the cypher adaptable ...

The further in the process the longer the cypher. Maybe timestamps can be included.
A base58 hash of every step's cypher to shorten the string?

I want to construct a website with all projects included, preferably decentralised running projects with centralised finalised projects.
Search with a hash, see the stage of the project and it's details.
Distinction must be made between public and private data, this means also enabling a login with password and authoization management.