---
layout: page
title: Status
description: Matthew Graybosch's microblog, also available in RSS as "status.xml"
permalink: /status/
---
# Status Updates

In addition to my main blog, where you might find posts that take over ten minutes to read, I also have a microblog where I post shorter updates and share links, pictures, and videos.

{% assign status = (site.status | sort: 'date' | reverse) %}
{% include status-loop.html %}