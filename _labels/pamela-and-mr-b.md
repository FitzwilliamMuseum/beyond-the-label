---
layout: default
title: Pamela and Mr B. in the summer house
slug: pamela-and-mr-b
---
{% assign data = site.data.labeldata | where:"slug", page.slug %}
<!-- {{ data }} -->
<img src="{{ data[0]object_1_cover_image }}" class="img-fluid"/>
<p>
Title: {{ data[0]object_1_title }} <br />
Object number: {{ data[0]object_1 }}<br />
Production: {{ data[0]object_1_production_information }}<br />

Label type: {{ data[0]label_type }} <br />
Displayed: {{ data[0]display_location }}<br />
Acquisition: {{ data[0]acquisition_credit_line }}<br />
</p>
