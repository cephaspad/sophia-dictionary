---
layout: page
title: English Vietnamese
---


<ul>
{% for entry in site.en_vn %}
    {% if entry.word %}
    <li><a href="{{ entry.url | replace:".html","" }}">{{ entry.word }}</a></li>
    {% endif %}
{% endfor %}
</ul>