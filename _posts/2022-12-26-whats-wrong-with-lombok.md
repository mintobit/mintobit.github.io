---
layout: post
title: "What's wrong with Lombok?"
date: 2022-12-26
post_image: /assets/images/elisa-ventur-bmJAXAz6ads-unsplash.jpg
tags: []
categories: [posts]
author: mintobit
comments: false
dark_header: false
---
# {{ page.title }}

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I&#39;m just studying for a Java dev. but I&#39;ve seen a lot of guys that are using Lombok. What&#39;s wrong with it?</p>&mdash; Artem Kuzyk (@ArtemKuzyk) <a href="https://twitter.com/ArtemKuzyk/status/1607130162063183872?ref_src=twsrc%5Etfw">December 25, 2022</a></blockquote>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">There are two assumptions that drive building tools like Lombok:<br>1. You can save time by typing less code<br>2. You can save time by reading less code<br><br>It certainly &quot;feels&quot; like both are true. But they are not.<br><br>1/4</p>&mdash; Anton Nizhegorodov 🇺🇦 (@mintobit) <a href="https://twitter.com/mintobit/status/1607144817926221824?ref_src=twsrc%5Etfw">December 25, 2022</a></blockquote>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Engineers spend most of their time *thinking*. Cognitive ability is the bottleneck of everything they do, including reading and writing code. So what happens when your read code annotated with Lombok?<br><br>2/4</p>&mdash; Anton Nizhegorodov 🇺🇦 (@mintobit) <a href="https://twitter.com/mintobit/status/1607144906190905347?ref_src=twsrc%5Etfw">December 25, 2022</a></blockquote>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Additional tasks for your brain:<br>- Your brain has to decompile annotations<br>- Your brain has to maintain a cache of decompiled annotations<br>- Your brain has to take into account behavior that it decompiled from annotations<br><br>3/4</p>&mdash; Anton Nizhegorodov 🇺🇦 (@mintobit) <a href="https://twitter.com/mintobit/status/1607145128690319360?ref_src=twsrc%5Etfw">December 25, 2022</a></blockquote>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">As a result, you become slower. Also, you may make an error during decompilation, which makes you even slower.<br><br>Reasons &quot;delombock&quot; feature exists:<br>- aid your brain to decompile annotations<br>- check that you made no errors during decompilation<br><br>4/4</p>&mdash; Anton Nizhegorodov 🇺🇦 (@mintobit) <a href="https://twitter.com/mintobit/status/1607145479187632129?ref_src=twsrc%5Etfw">December 25, 2022</a></blockquote>
