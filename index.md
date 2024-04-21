---
layout: default
title: some posting
---
## list of postings

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) {{ post.date }}
      {{ post.excerpt }}
{% endfor %}
