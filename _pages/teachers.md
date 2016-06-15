---
title: "Teachers"
layout: single
permalink: /teachers
author_profile: true
---

{% include about-site.html %}

All of this material is freely available to teachers and students under the <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

I encourage teachers to adapt this work to make it their own.

Additional <strong>quizzes and tests</strong> are available for free to teachers. Please contact me directly to obtain these:

{% include contact.html person='Ron' %}

All of these materials I designed with an approach to teaching and learning that I call <strong>Structured Independent Learning</strong>.

To learn more about <strong>Structured Independent Learning</strong> and how I came to develop this approach you can read a <a href='/docs/Structured%20Independent%20Learning/SIL%20narrative.pdf' target="newWindow">Structured Independent Learning Narrative</a>.

I have also included some sample calendars below to give examples of how I used these materials in a school year:

<div class="grid__wrapper"><ul>

{% assign subject='Physics 20' %}
{% assign subjpath = subject | split:" " | join: "" %}
{% assign linkitem = '/lessons/' | append:subjpath | append:'/calendars' %}

{% include card-item.html link-item=linkitem color='green' icon='calendar' description=subject type='grid' title='Calendars' %}

{% assign subject='Physics 30' %}
{% assign subjpath = subject | split:" " | join: "" %}
{% assign linkitem = '/lessons/' | append:subjpath | append:'/calendars' %}

{% include card-item.html link-item=linkitem color='green' icon='calendar' description=subject type='grid' title='Calendars' %}

{% assign subject='Chemistry 20' %}
{% assign subjpath = subject | split:" " | join: "" %}
{% assign linkitem = '/lessons/' | append:subjpath | append:'/calendars' %}

{% include card-item.html link-item=linkitem color='green' icon='calendar' description=subject type='grid' title='Calendars' %}

{% assign subject='Math 10c' %}
{% assign subjpath = subject | split:" " | join: "" %}
{% assign linkitem = '/lessons/' | append:subjpath | append:'/calendars' %}

{% include card-item.html link-item=linkitem color='green' icon='calendar' description=subject type='grid' title='Calendars' %}

</ul></div>

