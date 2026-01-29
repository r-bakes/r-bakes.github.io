---
layout: default
title: Blog
---

# Cool Stuff in Computer Science

---

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{% endfor %}
