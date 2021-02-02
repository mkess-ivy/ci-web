--- 
layout: theme002
permalink: /news/
title: News

bg-img: /img/ci-bg.jpg
---
{% include page_title.html name="News" desc="something interesting" %}

{% for item in site.posts %}
{{ item.header }}
{{ item.title }}
{% endfor %}