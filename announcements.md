---
layout: page
title: Announcements
description: >-
    Listing of all course announcements
---

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
