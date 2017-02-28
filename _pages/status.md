---
layout: page
title: Status
description: Matthew Graybosch's microblog, also available in RSS as "status.xml"
permalink: /status/
---

{% assign status = (site.sorted | sort: 'date') | reverse %}
{% include status-loop.html %}