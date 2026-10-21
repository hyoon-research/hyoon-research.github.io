---
layout: page
permalink: /publications/
title: Publications
description: ""
nav: true
nav_order: 3
---

## Selected Manuscripts and Preprints

<div class="publications">
{% bibliography --query @*[pubgroup=manuscript] --group_by none %}
</div>

## Peer-reviewed Journal Publications

<div class="publications">
{% bibliography --query @*[pubgroup=reviewed] --group_by year --group_order descending %}
</div>

## Technical Reports

<div class="publications">
{% bibliography --query @*[pubgroup=report] --group_by year --group_order descending %}
</div>
