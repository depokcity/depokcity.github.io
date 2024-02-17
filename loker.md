---
layout: page
title: "Loker Depok"
permalink: /loker/
---
{% for post in site.categories.loker %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
