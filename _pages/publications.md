---
title: "SACA - Publications"
layout: gridlay
excerpt: "SACA Group Publications."
sitemap: false
permalink: /publications/
---


# Peer-Reviewed Publications and PrePrints
{% for yr in site.data.publist %}
<h3>{{ yr.year }}</h3>
-----
{% for publi in yr.pubs %}

{% if publi.team=="NA" %}
  <b style="color:blue;"> <u> [{{ publi.link.display }}] </u> </b> &nbsp;
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.title }}</a> <br /> {{ publi.description }} 
{% else %}
 <b>[{{ publi.link.display }}] </b> &nbsp;
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.title }}</a> <br /> {{ publi.description }}
{% endif %}

{% endfor %}
{% endfor %}

