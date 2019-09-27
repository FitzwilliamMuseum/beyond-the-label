---
title: Portrait statuette of George Frideric Handel (1685-1759)
layout: default
slug: handel
---
{% assign data = site.data.labeldata | where:"slug", page.slug %}
<!-- {{ data }} -->
<img src="{{ data[0]object_1_cover_image string }}" />
<p>
Title: {{ data[0]object_1_title string}} <br />
Object number: {{ data[0]object_1 string }}<br />
Production: {{ data[0]object_1_production_information string}}<br />

Label type: {{ data[0]label_type string }} <br />
Displayed: {{ data[0]display_location string }}<br />
Acquisition: {{ data[0]acquisition_credit_line string }}<br />
</p>
