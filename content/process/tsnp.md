+++
date = '2026-03-04T00:25:14+09:00'
tags = ["software engineering","C++"]
title = 'tsnp'
status = "in progress"
+++

Switching over to Linux was something I've done a really long time ago,
and it was a decision that I'm much happier for. Nevertheless, every time
I find myself needing to sketch something simple out for myself, there's
nothing really as "correct" feeling as MS Paint was when I had been daily
driving Windows. It's an experience I feel like it's due time I solve.

Is it just that no Unix alternatives exist? They probably do, but I haven't
tried any of them. I like GIMP, but feels like overkill when all I need is some
digital scratch paper. I'm on the browser all the time anyways (for after 
all has that not become the purpose of the OS?), so I've been using Excalidraw
as the convenient arms-length option, but it feels bad to use for me personally.

With that in mind, I'm creating tsnp. tsnp aims to be a simple, low-friction 
MS Paint equivalent for Linux. It's a small, personal group project I'm working 
on with my college friends as our first attempt at making some actually 
usable software. 

The real reason is I thought this would be an easy project and it would be
fun to implement my own things sometimes. Let's see how catastrophically wrong
I am. There will be rookie mistakes.

## Where to start

So, paint substitute. My friend wanted to use this as an opportunity to learn
C++, so the first thing I needed to figure out was the tech stack.

Fun fact: I've never worked with C++ before. In general, I am a very fresh
programmer and I don't have a lot of experience with working on fully fledged
projects. Like, ones where you have to put things in directories, and write
a build script, and compile it, instead of relying on the OS and stringing 
together a bunch of shell scripts with duct tape and symlinks. Not that the
general principle was any different (i.e. pay attention to your data structures!),
but this seemed like a different, more involving workflow, and this was a novel and
intimidating challenge to me.
