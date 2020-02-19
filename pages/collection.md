---
layout: page
title: Browse the Collection
permalink: /collection/
---


{% include collection_gallery.html facet_by='' collection='lift' %}

<ul>
    {% for item in site.lift %}
        <li><a href="{{ site.baseurl }}/lift/{{ item.pid }}/">{{ item.label }}</a></li>
    {% endfor %}
</ul>



