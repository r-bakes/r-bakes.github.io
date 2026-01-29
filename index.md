---
layout: default
title: Blog
---

# Neat Stuff

> A collection of articles on varied topics in computer science and software that were interesting enough to warrant deeper reflection.

---

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{% endfor %}
