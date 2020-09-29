---
title: Welcome
navbar: Home
---

<article class="message is-usf-gold">
  <div class="message-header">
    <p>Getting Started with Remote Learning</p>
  </div>
  <div class="message-body">
    The first week of lectures will be conducted synchronously via Zoom. See the <a href="/guides/general/getting-started.html">Getting Started</a> guide for details on how to join and what to expect for your first day.
  </div>
</article>

Welcome to <strong class="has-text-usf-green">CS {{ site.data.info.code }} {{ site.data.info.name }}</strong> for <strong class="has-text-usf-green">{{ site.data.info.term }}</strong>. {{ site.data.info.blurb }}

## Upcoming Schedule

Here is the upcoming course schedule, which includes links to lecture material, assigned quizzes and homework, and more:

<style>
ul.icons {
  list-style-type: none;
  margin-left: 1.5em;
  margin-top: 0em;
}

ul.icons > li {
  position: relative;
}

ul.icons > li > i {
  width: 1.25em;
  left: -1.5em;
  position: absolute;
  text-align: center;
  line-height: inherit;
}

.content li.bump {
  margin-top: 0.8rem;
}
</style>

{%- assign today_date = 'now' | date: '%Y-%m-%d' -%}
{%- assign today = today_date | date: '%s'| abs -%}
{%- assign beg_date = '2020-08-18' | date: '%s' | abs -%}
{%- assign beg_index = 0 -%}

{%- if today > beg_date -%}
  {%- assign end_index = site.data.schedule.weeks | size | minus: 1 -%}

  {%- for week in site.data.schedule.weeks limit:end_index -%}
    {%- if week.date -%}
      {%- assign as_seconds = week.date | date: '%s' | abs -%}
      {%- if as_seconds > today -%}
        {%- break -%}
      {%- endif -%}
    {%- endif -%}
    {%- assign beg_index = forloop.index0 -%}
  {%- endfor -%}

  {%- assign beg_index = beg_index | minus: 1 -%}
{%- endif -%}

{% for week in site.data.schedule.weeks offset:beg_index limit:3 %}
{% include week.html week = week %}
{% endfor %}

## Weekly Overview

Find the regular weekly schedule below. Note this may change due to holidays, additions, or cancellations. Always check the [Canvas]({{ side.data.info.links.canvas.link }}) calendar for the most recent schedule.

{% include overview.html %}

## Navigation

This website serves as the main portal for all content related to this course. To navigate this site:

<ul class="fa-ul" style="margin-left: 1in;">
{% for item in site.data.info.pages -%}
  <li>
  {% if item.icon -%}
    <span class="fa-li"><i class="{{ item.icon }}"></i></span>
  {% endif -%}
    <a href="{{ item.link | relative_url }}">{{ item.name }}</a>: {{ item.info }}
  </li>
{% endfor -%}
{% for values in site.data.info.links -%}
  {% assign label = values[0] -%}
  {% assign item = site.data.info.links[label] -%}
  <li {% if forloop.first or item.line %}class="bump"{% endif %}>
  {% if item.icon -%}
    <span class="fa-li"><i class="{{ item.icon }}"></i></span>
  {% endif -%}
    <a href="{{ item.link | relative_url }}">{{ item.name }}</a>: {{ item.info }}
  </li>
{% endfor -%}

  <li class="bump">
    <span class="fa-li"><i class="far fa-signal-stream"></i></span>
    Zoom: dropdown containing all of the Zoom meetings relevant to this course
  </li>
</ul>

When in doubt, post on [Piazza]({{ site.data.info.links.piazza.link }}) for help finding content.