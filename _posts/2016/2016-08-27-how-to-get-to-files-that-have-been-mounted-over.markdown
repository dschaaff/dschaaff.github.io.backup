---
author: dschaaff
comments: true
date: 2016-08-27 16:27:39+00:00
layout: post
link: http://danielschaaff.com/2016/08/27/how-to-get-to-files-that-have-been-mounted-over/
slug: how-to-get-to-files-that-have-been-mounted-over
title: How to get to files that have been mounted over
wordpress_id: 549
categories:
- techology
tags:
- linux
- mounts
---

You have a directory with data, and now you've mounted a volume over it. How do you get to the data in the underlying directory without interrupting the mounted volume? Bind mount to the rescue!
Bind mount the directory to another path and you can manipulate the files in underlying directory without disturbing the volume mounted atop of it.
