---
layout: default
title: 四时之花 300
---
#{{ page.title }}

##想写一个博客来记录身边的花草。

　　　　{% for post in site.posts %}
　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　　　　{% endfor %}
