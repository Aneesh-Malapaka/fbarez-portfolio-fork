---
title: "Archive Layout with Content"
layout: archive
permalink: /archive-layout-with-content/
---



This allows you to denote <var>variables</var>.

{% include base_path %}
{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}
