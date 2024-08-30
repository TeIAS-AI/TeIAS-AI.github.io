---
title: "News"
layout: textlay
excerpt: "LLMs Lab at TeIAS."
sitemap: false
permalink: /teias.isntitute
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
