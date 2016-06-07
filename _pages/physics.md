---
title: "Physics"
layout: single
permalink: /physics
author_profile: false
---

{% include base_path %}

<div class="grid__wrapper"><ul>

{% assign subject = "Physics 20" %}

{% assign units = "" | split:"|"  %}
{% for lesson in site.data.lessons %}
 {% if lesson.subject == subject %}
    {% assign proceedforth = true %}
    {% assign units = units | push: lesson.unit %}
 {% endif %}
{% endfor %}
{% assign units = units | uniq %}

{% assign subjpath = subject | split:" " | join: "" %}

{% assign nunit = 1 %}
{% for unit in units %}
 {% include subject-unit.html unit=unit nunit=nunit subjpath=subjpath type='grid' subject=subject %}
 {% assign nunit = nunit | plus:1 %}
{% endfor %}

{% assign subject = "Physics 30" %}

{% assign units = "" | split:"|"  %}
{% for lesson in site.data.lessons %}
 {% if lesson.subject == subject %}
    {% assign proceedforth = true %}
    {% assign units = units | push: lesson.unit %}
 {% endif %}
{% endfor %}
{% assign units = units | uniq %}

{% assign subjpath = subject | split:" " | join: "" %}

{% assign nunit = 1 %}
{% for unit in units %}
 {% include subject-unit.html unit=unit nunit=nunit subjpath=subjpath type='grid' subject=subject %}
 {% assign nunit = nunit | plus:1 %}
{% endfor %}

</ul></div>

