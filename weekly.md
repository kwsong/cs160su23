---
layout: page
title: Rooms & Times
description: The weekly event schedule.
nav_order: 3
---

# Rooms & Times
Below is the recurring weekly schedule (with rooms) for studio/lecture, discussion sections, and TA office hours. Changes and exceptions on specific days are announced on Slack.

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
