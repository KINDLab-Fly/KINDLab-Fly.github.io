---
title: "KIND Lab - Seminar"
layout: gridlay
excerpt: "KIND Lab: Seminar"
sitemap: false
permalink: /seminar/
---

## KIND Lab Weekly Seminar

The KIND Lab hosts a weekly paper reading seminar every Friday, where lab members take turns presenting cutting-edge research in knowledge graphs, graph machine learning, social network analysis, and related areas. The seminar fosters collaborative learning, critical thinking, and keeps our team up-to-date with the latest advances in the field. All members are encouraged to participate and engage in open discussion.

---

## Schedule

<table class="table table-striped">
  <thead>
    <tr>
      <th>Date (Friday)</th>
      <th>Presenter</th>
      <th>Paper</th>
    </tr>
  </thead>
  <tbody>
  {% for entry in site.data.seminar %}
  {% unless entry.date == nil %}
    <tr>
      <td>{{ entry.date }}</td>
      <td>{{ entry.presenter }}</td>
      <td>
        {% if entry.link %}
          <a href="{{ entry.link }}" target="_blank">{{ entry.paper }}</a>
        {% else %}
          {{ entry.paper }}
        {% endif %}
      </td>
    </tr>
  {% endunless %}
  {% endfor %}
  {% if site.data.seminar.size == 0 %}
    <tr><td colspan="3"><i>Schedule coming soon.</i></td></tr>
  {% endif %}
  </tbody>
</table>
