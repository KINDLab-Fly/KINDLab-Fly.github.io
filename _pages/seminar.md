---
title: "KIND Lab - Seminar"
layout: gridlay
excerpt: "KIND Lab: Seminar"
sitemap: false
permalink: /seminar/
---

## AI Weekly Seminar@KIND

The AI Weekly Seminar@KIND is a weekly seminar held every Friday, open to everyone interested in cutting-edge AI and machine learning research. Presenters may cover trendy topics in AI/ML, including agentic AI, large language models, retrieval-augmented generation, reasoning, and more, as well as domain-specialized research such as social network analysis, personalization, and natural disaster informatics. We welcome participants not only from within the KIND Lab but from any group or background who share a passion for advancing AI research.

> 🍕 Snacks and food will be provided from time to time!

---

## Location

**In-person:** Deschutes Hall 200<br>
**Zoom:** [https://uoregon.zoom.us/j/4052006678](https://uoregon.zoom.us/j/4052006678)

---

## Schedule

<table class="table table-striped">
  <thead>
    <tr>
      <th>Date (Friday)</th>
      <th>Time</th>
      <th>Presenter</th>
      <th>Paper</th>
    </tr>
  </thead>
  <tbody>
  {% for entry in site.data.seminar %}
  {% unless entry.date == nil %}
    <tr>
      <td>{{ entry.date }}</td>
      <td>{{ entry.time }}</td>
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
