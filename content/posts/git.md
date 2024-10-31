---
title: "Build Your Own Git Client"
description: "This project is to build a Git client."
tags: [unix, cli, git]
categories: [command line tools, vcs]
ShowToc: true
TocOpen: true
---

Git is a version control system created in 2005 by Linus Torvalds when he wanted a distributed system but none of the available free systems met his needs.

In a great example of how performance should be considered for software, he gave a concrete example of the performance problem to be solved; a source-control management system needing 30 seconds to apply a patch and update all associated metadata. Then he explaining that this would not scale to the needs of Linux kernel development, where synchronising with fellow maintainers could require 250 such actions at a time.

Therefore he specified that patching should take no more than three seconds. He added a couple more requirements: CVS was an example of what NOT to do and have very strong safeguards against corruption, either accidental or malicious.

The net result was that we, the software development community, ended up with a fast, distributed version control system which was free. As a result it has become the de facto industry standard.

Oh and the name, Linus Torvalds described git as "the stupid content tracker" and has said that the name (depending on your mood) can mean:

⇢ random three-letter combination that is pronounceable, and not actually used by any common UNIX command. The fact that it is a mispronunciation of "get" may or may not be relevant.

⇢ stupid. contemptible and despicable. simple. Take your pick from the dictionary of slang.

⇢ "global information tracker": you're in a good mood, and it actually works for you. Angels sing, and a light suddenly fills the room.

⇢ "goddamn idiotic truckload of sh*t": when it breaks.

<!--more-->

[Build your own git](https://codingchallenges.fyi/challenges/challenge-git) is available with a project breakdown on [Coding Challenges](https://codingchallenges.fyi/).