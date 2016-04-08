---
title: About Me
menu: About
---
{% assign current_year = site.time | date: '%Y' %}

Kaiyuan Liu
===

## Who am I

Driven, dynamic and highly qualified software engineer with a broad range of experience in technical
software development. Responsible for architectural design and implementation of web systems, mainly
focus on server-side development with Java and PHP. Also has front-end development with HTML, CSS, and JavaScript.

## keywords
<div class="btn-inline">
{% for keyword in site.skill_keywords %} <button class="btn btn-outline" type="button">{{ keyword }}</button> {% endfor %}
</div>
