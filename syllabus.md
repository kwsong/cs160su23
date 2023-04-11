---
layout: page
title: Syllabus
description: Syllabus with listing of course modules and topics.
nav_order: 2
---
# Syllabus

Note: Topics and readings may change slightly. Links to lecture slides, as well as any recordings, will be posted after the class they are introduced.

For ease of access, here are direct links to all lecture slides, section slides, and project materials. All other important forms, links, and resources are available on the BCourses homepage and pinned to the #resources-and-links channel in Slack.

## Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}
