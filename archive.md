---
layout: page
title: POST ARCHIVES
---

## links to previous posts:

{% for post in site.posts %}
  * {{ post.date | date: "%B %-d, %Y" }} &#10132; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
