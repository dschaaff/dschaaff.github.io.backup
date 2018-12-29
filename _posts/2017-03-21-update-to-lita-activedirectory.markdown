---
author: dschaaff
comments: true
date: 2017-03-21 02:24:20+00:00
layout: post
link: http://danielschaaff.com/2017/03/20/update-to-lita-activedirectory/
slug: update-to-lita-activedirectory
title: Update to lita-activedirectory
wordpress_id: 780
categories:
- ruby
- techology
tags:
- chatbot
- chatops
- lita
---

I updated our Active Directory lita plugin today with support for querying the members of a given group. See [https://github.com/knuedge/lita-activedirectory](https://github.com/knuedge/lita-activedirectory). It still needs some work to properly present errors when a user or group doesn't actually exist in the directory. Right now it returns nothing rather then a helpful error. It works splendidly with legit users and groups however.

ChatOps ftw!
