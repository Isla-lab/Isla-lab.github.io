---
title: "News"
layout: textlay
excerpt: "ISLa - Intelligent Systems Lab"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}