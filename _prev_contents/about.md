---
layout: home
title: Home
nav_order: 0
permalink: /:path/
description: >-
    Course policies and information.
---

## Advanced Natural Language Processing
{: .mb-2 }
Fall 2024
{: .mb-2 .fs-6 .text-grey-dk-000 }

{% if site.announcements %}
{{ site.announcements.last }}
{% endif %}


{% for module in site.modules %}
{{ module }}
{% endfor %}





