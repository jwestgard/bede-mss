---
title: Works
title-display: List of Bede's Works
mod-date: 2014-01-19
layout: default
---

{% assign works = site.data.bedeworks %}

<p>What follows is a list of Bede's works, generated from a JSON data file.</p>

<ol>
    {% for work in works %}
        <li><cite>{{ work.Latin }}</cite> / <cite>{{ work.English }}</cite> ({{ work.CPL }})</li>
    {% endfor %}
</ol>
