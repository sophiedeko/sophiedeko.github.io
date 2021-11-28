---
layout: default
title: sophie's blog
regenerate: true
---

# {{page.title}}

Welcome to my blog!

{% for post in site.post %}
## <a href="{{ post.url }}">{{ post.title }}</a>

{{ post.excerpt }}

{% endfor %}