---
layout: default
title: some posting
---
## list of postings

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) {{ post.date }}
      {{ post.excerpt }}
{% endfor %}
