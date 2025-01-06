---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

Deliverables marked **Project**{:.label .label-red} should be delivered by the team. Deliverables marked **Homework**{:.label .label-yellow} or **Reading**{:.label .label-blue} should be completed individually.

Deliverables are listed on the days on which they are **due** except as noted.

{% for module in site.modules %}
{{ module }}
{% endfor %}
