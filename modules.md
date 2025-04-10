---
layout: page
title: Modules
description: >-
    Listing of course modules.
nav_order: 3
---

# Modules

A draft of the lecture slides for each module
will be made available the evening before the module begins.
The final version of the lecture slides will be made available
after the module is completed and replaces the draft.
**Use of the draft is at your own risk!**

Readings marked as mandatory contain required material for the course,
and must be read before the date of the corresponding lecture.

{% assign modules = site.modules | where: 'type', 'module' %}
{% for module in modules %}
{{ module }}
{% endfor %}
