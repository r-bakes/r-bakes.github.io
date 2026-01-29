---
layout: default
title: Blog
---

> One must imagine.

---

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{% endfor %}
