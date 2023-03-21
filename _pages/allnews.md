---
title: "ISLa - News"
layout: textlay
excerpt: "ISLa Group at the University of Verona."
sitemap: false
permalink: /news/
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<b>{{ article.headline }}</b> <br>
<em> {{ article.descr }} </em></p>
{% endfor %}
