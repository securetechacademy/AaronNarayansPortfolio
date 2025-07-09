---
layout: default
---

# Blog Posts

{% for post in site.posts %}
- Link Test: {{ site.baseurl }}{{ post.url }}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
