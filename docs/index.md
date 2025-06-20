---
layout: default
title: UCMJ Survival Guide
---

# Welcome to the UCMJ Survival Guide

**By Michael Waddington & Alexandra González-Waddington**

This is the official GitHub Pages version of the *UCMJ Survival Guide*, designed to help military personnel and families navigate the complex world of military justice.

## 📘 Explore the Guide

Click a chapter below to begin reading:

{% for file in site.static_files %}
  {% if file.path contains 'chapters' and file.extname == '.md' %}
  - [{{ file.name | replace: '-', ' ' | replace: '.md', '' | capitalize }}]({{ file.path | relative_url }})
  {% endif %}
{% endfor %}

## 🔗 About the Authors

Michael Waddington and Alexandra González-Waddington are globally recognized military defense lawyers who have represented service members in some of the most high-profile court-martials in recent history.

👉 Visit [https://ucmjdefense.com](https://ucmjdefense.com) for full legal resources.
