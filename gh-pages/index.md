---
layout: default
title: sophie's blog
regenerate: true
---

# {{page.title}}

{{ site.description }}

{% for post in site.posts %}
## <a href="{{ post.url }}">{{ post.title }}</a>

{{ post.excerpt }}

{% endfor %}