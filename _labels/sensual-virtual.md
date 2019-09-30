---
title: Sensual Virtual
layout: default
slug: sensual-virtual
---
{% assign data = site.data.labeldata | where:"slug", page.slug %}

{{ data[0]label_content}}

<span class="mb-1 mt-1 badge badge-dark p-2">{{ data[0]display_location }}</span>
