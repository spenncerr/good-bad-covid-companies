---
title: UK Company Reactions to Covid-19
layout: default
---

### Good
<ul class="listing">
  {%- for item in sheet.Good -%}
    <li><strong>{{ item.company }}</strong> - {{ item.reaction }}</li>
  {%- endfor -%}
</ul>

### Bad
<ul class="listing">
  {%- for item in sheet.Bad -%}
    <li><strong>{{ item.company }}</strong> - {{ item.reaction }}</li>
  {%- endfor -%}
</ul>

A quick [Eleventy](https://www.11ty.io/) project inspired by [Andy Bell](https://twitter.com/hankchizljaw) with data collected by [Catherine Oliver](https://twitter.com/katiecmoliver/).