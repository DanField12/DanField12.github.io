---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Dan's Blog
---

Hi, I'm Dan and welcome to my blog. Here you can find rants about my software projects or any other things I am passionate about.

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


