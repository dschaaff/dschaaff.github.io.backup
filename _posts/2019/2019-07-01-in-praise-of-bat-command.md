---
author: dschaaff
comments: true
date: 2019-07-01
layout: post
slug: in-praise-of-the-bat-command-line-tool
title: 'In Praise of the Bat Commandline Tool'
categories:
- tools
- techology
- cli
tags:
- tools
- techology
- cli
---

I’ve been workng on helm charts a lot lately. For better or worse that has involved running `helm install —debug —dry-run…` a lot to ensure things render correctly. It is much easier to parse that output when there is syntax highlighting. Enter [bat]([GitHub - sharkdp/bat: A cat(1) clone with wings.](https://github.com/sharkdp/bat)). I can `helm install —debug —dry-run… | bat -l yams` to get full syntax highlighting.  It’s a small thing but it makes a big difference.

[GitHub - sharkdp/bat: A cat(1) clone with wings.](https://github.com/sharkdp/bat)
