---
layout: page
title: Newton-Cartan Gravity
permalink: "/newton-cartan-gravity"
---

{% assign papers = site.posts | where_exp: "post", "post.topics contains 'newton-cartan-gravity'" %}

{% for paper in papers %}
- [{{ paper.title }}]({{ paper.url | relative_url }})
{% endfor %}
