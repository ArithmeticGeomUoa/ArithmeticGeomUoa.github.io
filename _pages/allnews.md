---
title: "News"
layout: textlay
excerpt: "Arithmetic Geometry at National and Kapodistrian University of Athens."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
