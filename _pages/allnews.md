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
<em>{{ article.headline }}</em></p>
{% endfor %}



{% for article in site.data.news limit:9 %}
  <div class="news-item" style="margin-bottom: 20px;">
    <p><strong>{{ article.date }}</strong></p>

    {% if article.link %}
      <h3><a href="{{ article.link }}" target="_blank" rel="noopener noreferrer">{{ article.headline }}</a></h3>
    {% else %}
      <h3>{{ article.headline }}</h3>
    {% endif %}

    {% if article.image %}
      <a href="{{ article.image }}" target="_blank" rel="noopener noreferrer">
        <img src="{{ article.image }}" alt="News image" style="max-width:100%; height:auto; margin:10px 0;">
      </a>
    {% endif %}

    {% if article.description %}
      <p>{{ article.description }}</p>
    {% endif %}
  </div>
{% endfor %}