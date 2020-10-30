---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Dan's Blog
---

## Subtitle


<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


