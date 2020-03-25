---
title: UK Company Reactions to Covid-19
layout: default
---

<div class="companies">
  <div class="companies__column">
    <h2>Good</h2>
    <ul class="listing">
      {%- for item in sheet.Good -%}
        <li><strong>{{ item.company }}</strong> - {{ item.reaction }}</li>
      {%- endfor -%}
    </ul>
  </div>

  <div class="companies__column">
    <h2>Bad</h2>
    <ul class="listing">
      {%- for item in sheet.Bad -%}
        <li><strong>{{ item.company }}</strong> - {{ item.reaction }}</li>
      {%- endfor -%}
    </ul>
  </div>
</div>

A quick [Eleventy](https://www.11ty.io/) project built by [Spencer Haizel](https://twitter.com/spenncerr) inspired by [Andy Bell](https://twitter.com/hankchizljaw) with data collected by [Catherine Oliver](https://twitter.com/katiecmoliver/).