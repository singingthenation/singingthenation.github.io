---
layout: page
title: Browse the Collection
permalink: /collection/
---

This site's sample collection comprises a set of objects, each of which is below. 

# Browse the Collection

{% include collection_gallery.html facet_by='performer' collection='lift' %}

<ul>
    {% for item in site.lift %}
        <li><a href="{{ site.baseurl }}/lift/{{ item.pid }}/">{{ item.label }}</a></li>
    {% endfor %}
</ul>



