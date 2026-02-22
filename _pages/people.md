---
title: "KIND Lab - Members"
layout: gridlay
excerpt: "KIND Lab: Members"
sitemap: false
permalink: /people/
---


## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row" style="display: flex; flex-wrap: wrap;">
{% endif %}

<div class="col-sm-6" style="margin-bottom: 20px; display: flex;">
  <div style="display: flex; align-items: flex-start; width: 100%; gap: 12px;">
    <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" style="width: 80px; height: 80px; object-fit: cover; flex-shrink: 0; margin: 8px 0 0 0;" />
    <div style="flex: 1; min-width: 0;">
      <h4 style="margin-top: 8px; margin-bottom: 2px;">{{ member.name }}</h4>
      <div><i>{{ member.info }}</i></div>
      <div style="margin-bottom: 6px; color: #555; font-size: 0.9em;">{{ member.email }}</div>
      <ul style="margin: 2px 0; padding-left: 18px; overflow: hidden;">
        {% if member.education1 %}<li style="font-size: 0.9em;">{{ member.education1 }}</li>{% endif %}
        {% if member.education2 %}<li style="font-size: 0.9em;">{{ member.education2 }}</li>{% endif %}
        {% if member.education3 %}<li style="font-size: 0.9em;">{{ member.education3 }}</li>{% endif %}
        {% if member.education4 %}<li style="font-size: 0.9em;">{{ member.education4 }}</li>{% endif %}
        {% if member.education5 %}<li style="font-size: 0.9em;">{{ member.education5 }}</li>{% endif %}
      </ul>
      <div class="social-links" style="margin-top: 6px;">
        {% if member.website != 0 %} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
        {% if member.scholar != 0 %} <a href="{{ member.scholar }}"> <i class="fa fa-scholar"></i></a> {% endif %}
        {% if member.linkedin != 0 %} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
        {% if member.github != 0 %} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
        {% if member.twitter != 0 %} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %}
      </div>
    </div>
  </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<br>













## PhDs
{% assign number_printed = 0 %}
{% for member in site.data.phd %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row" style="display: flex; flex-wrap: wrap;">
{% endif %}

<div class="col-sm-6" style="margin-bottom: 20px; display: flex;">
  <div style="display: flex; align-items: flex-start; width: 100%; gap: 12px;">
    <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" style="width: 80px; height: 80px; object-fit: cover; flex-shrink: 0; margin: 8px 0 0 0;" />
    <div style="flex: 1; min-width: 0;">
      <h4 style="margin-top: 8px; margin-bottom: 2px;">{{ member.name }}</h4>
      <div><i>{{ member.info }}</i></div>
      <div style="margin-bottom: 6px; color: #555; font-size: 0.9em;">{{ member.email }}</div>

      {% if member.education1 %}
      <div><strong>Research:</strong>
        <ul style="margin: 2px 0 4px 0; padding-left: 18px;">
          <li style="font-size: 0.9em;">{{ member.education1 }}</li>
        </ul>
      </div>
      {% endif %}

      {% if member.education2 or member.education3 or member.education4 or member.education5 %}
      <div><strong>Awards & Notes:</strong>
        <ul style="margin: 2px 0 4px 0; padding-left: 18px;">
          {% if member.education2 %}<li style="font-size: 0.9em;">{{ member.education2 }}</li>{% endif %}
          {% if member.education3 %}<li style="font-size: 0.9em;">{{ member.education3 }}</li>{% endif %}
          {% if member.education4 %}<li style="font-size: 0.9em;">{{ member.education4 }}</li>{% endif %}
          {% if member.education5 %}<li style="font-size: 0.9em;">{{ member.education5 }}</li>{% endif %}
        </ul>
      </div>
      {% endif %}

      <div class="social-links" style="margin-top: 6px;">
        {% if member.website != 0 %} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
        {% if member.linkedin != 0 %} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
        {% if member.github != 0 %} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
        {% if member.twitter != 0 %} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %}
      </div>
    </div>
  </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<br>
<br>




## Masters
{% assign number_printed = 0 %}
{% for member in site.data.ms %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row" style="display: flex; flex-wrap: wrap;">
{% endif %}

<div class="col-sm-6" style="margin-bottom: 20px; display: flex;">
  <div style="display: flex; align-items: flex-start; width: 100%; gap: 12px;">
    <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" style="width: 80px; height: 80px; object-fit: cover; flex-shrink: 0; margin: 8px 0 0 0;" />
    <div style="flex: 1; min-width: 0;">
      <h4 style="margin-top: 8px; margin-bottom: 2px;">{{ member.name }}</h4>
      <div><i>{{ member.info }}</i></div>
      <div style="margin-bottom: 6px; color: #555; font-size: 0.9em;">{{ member.email }}</div>
      {% if member.education1 %}
      <ul style="margin: 2px 0; padding-left: 18px;">
        <li style="font-size: 0.9em;">{{ member.education1 }}</li>
        {% if member.education2 %}<li style="font-size: 0.9em;">{{ member.education2 }}</li>{% endif %}
        {% if member.education3 %}<li style="font-size: 0.9em;">{{ member.education3 }}</li>{% endif %}
        {% if member.education4 %}<li style="font-size: 0.9em;">{{ member.education4 }}</li>{% endif %}
      </ul>
      {% endif %}
      <div class="social-links" style="margin-top: 6px;">
        {% if member.website != 0 %} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
        {% if member.linkedin != 0 %} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
        {% if member.github != 0 %} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
      </div>
    </div>
  </div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<br>
<br>











## Undergraduates
{% assign number_printed = 0 %}
{% for member in site.data.bs %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row" style="display: flex; flex-wrap: wrap;">
{% endif %}

<div class="col-sm-6" style="margin-bottom: 20px; display: flex;">
  <div style="display: flex; align-items: flex-start; width: 100%; gap: 12px;">
    <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" style="width: 80px; height: 80px; object-fit: cover; flex-shrink: 0; margin: 8px 0 0 0;" />
    <div style="flex: 1; min-width: 0;">
      <h4 style="margin-top: 8px; margin-bottom: 2px;">{{ member.name }}</h4>
      <i>{{ member.info }}</i>
      {% if member.education1 %}
      <ul style="margin: 4px 0; padding-left: 18px;">
        <li style="font-size: 0.9em;">{{ member.education1 }}</li>
        {% if member.education2 %}<li style="font-size: 0.9em;">{{ member.education2 }}</li>{% endif %}
        {% if member.education3 %}<li style="font-size: 0.9em;">{{ member.education3 }}</li>{% endif %}
        {% if member.education4 %}<li style="font-size: 0.9em;">{{ member.education4 }}</li>{% endif %}
        {% if member.education5 %}<li style="font-size: 0.9em;">{{ member.education5 }}</li>{% endif %}
      </ul>
      {% endif %}
      <div class="social-links" style="margin-top: 6px;">
        {% if member.linkedin != 0 %} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
        {% if member.github != 0 %} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
      </div>
    </div>
  </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<br>
<br>
