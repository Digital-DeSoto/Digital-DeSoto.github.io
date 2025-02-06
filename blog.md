---
layout: default
title: Blog
---
# Blog
Stay updated with the latest insights and trends in AI and data analytics.

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%B %d, %Y" }}
{{ post.excerpt }}
{% endfor %}