---
layout: default
title: White Rabbit
permalink: authors/rabbit/
---
This is an example description.

{% assign author_posts = site.posts | where:"author","rabbit" %}
{% include author.html %}