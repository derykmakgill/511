---
layout: home
title: Breaking Satoshi
---

# Welcome

*Breaking Satoshi* is a Bitcoin analysis site. We plan to produce several collections, or 'seasons,' of essays once a quarter about the most important questions in Bitcoin, written by Deryk Makgill and occasional guests. [Season 1](/season-1) is under development and will be announced soon.

The lengthier essays will be accompanied by a more regular blog and [newsletter.](https://breakingsatoshi.substack.com/)

Follow via Twitter ([@breakingsatoshi](https://twitter.com/breakingsatoshi)).

## Read

Some of our most recent posts:

{% for post in site.posts %} [{{ post.title }}]({{ post.url }}) » {{ post.date | date_to_string }} {% endfor %}
