---
title: "News"
layout: textlay
excerpt: "Group Acting on Curves."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em> 
{% if article.link %}
        <a href="{{ article.link }}" target="_blank" rel="noopener noreferrer">
          {{ article.headline }}
        </a>
      {% else %}
        {{ article.headline }}
      {% endif %}
</em><br>
<img src="{{ article.image }}" alt="News image" style="max-width:100%; height:auto;"></p>
{% endfor %}



