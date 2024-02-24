---
layout: default
title: Black Cat
author: cat
permalink: authors/cat/
---
This is an example description.

{% assign author_posts = site.posts | where:"author","cat" %}
{% include author.html %}