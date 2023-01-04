---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

Deliverables marked **Project**{:.label .label-red} should be delivered by the team. Deliverables marked **Homework**{:.label .label-yellow} or **Reading**{:.label .label-blue} should be completed individually.

{% for module in site.modules %}
{{ module }}
{% endfor %}
