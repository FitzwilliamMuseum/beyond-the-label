---
layout: default
title: The Founder's Building
slug: founders-building
---
{% assign data = site.data.labeldata | where:"slug", page.slug %}

{{ data[0]label_content}}
