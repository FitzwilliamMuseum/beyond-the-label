---
layout: default
title: The Hon. Richard Fitzwilliam, later 7th Viscount Fitzwilliam of Merrion
slug: richard-fitzwilliam
---
{% assign data = site.data.labeldata | where:"slug", page.slug %}
<!-- {{ data }} -->
<img src="{{ data[0]object_1_cover_image string }}" class="img-fluid"/>
<p>
Title: {{ data[0]object_1_title string}} <br />
Object number: {{ data[0]object_1 string }}<br />
Production: {{ data[0]object_1_production_information string}}<br />

Label type: {{ data[0]label_type string }} <br />
Displayed: {{ data[0]display_location string }}<br />
Acquisition: {{ data[0]acquisition_credit_line string }}<br />
</p>
