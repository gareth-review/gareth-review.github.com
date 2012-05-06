---
layout: post
title: Introducing Gareth...
categories: progress
---
I started Gareth a number of weeks ago. Progress has been made in various parts of the project but haven't been cataloged besides a poke here or there to various people.

To introduce Gareth I'm going to be making separate posts for various parts of the system which have already been implemented to introduce what I've already written before I move on to current progress.

Before I move on to features I'll get backend out of the way.

Gareth was initially written in plain PHP. Chunks of MediaWiki were being abstracted and used for the project. Around the time that user handling was going to be started I decided that all that from scratch PHP was slowing down the project's ability to move forward quickly.

Hence Gareth was then rewrote to use Symfony. It didn't take all that long to rewrite from that state and the project moved forward. But as the project moved forward issue after issue came up with Symfony. Bugs in Symfony itself lead to several days of development time being lost trying to debug issues caused by bugs in Symfony.

After hitting a bug that looked unfixable Gareth was again rewritten. This time it was rewritten in Python using Django. And the project has moved forwards since then. Django has had one or two bumps in the way but they've generally been fixable in a fair amount of time.