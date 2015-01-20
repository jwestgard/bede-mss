---
title: Test
title-display: Test Data
mod-date: 2014-01-19
layout: default
---
{% assign items = site.data.testdata | sort %}

<p>What follows is some data.</p>

<ul>
    {% for item in items %}
        <li>{{ item }}</li>
    {% endfor %}
</ul>
