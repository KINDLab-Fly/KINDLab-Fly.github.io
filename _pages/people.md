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
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">
    {% for i in (1..member.number_educ) %}
    <li>{{ member["education" | append: i] }}</li>
    {% endfor %}
  </ul>
  <div class="social-links"> 
    {% if member.website != 0 %}<a href="{{ member.website }}"><i class="fa fa-link"></i></a>{% endif %}
    {% if member.scholar != 0 %}<a href="{{ member.scholar }}"><i class="fa fa-scholar"></i></a>{% endif %}
    {% if member.linkedin != 0 %}<a href="{{ member.linkedin }}"><i class="fa fa-linkedin"></i></a>{% endif %}
    {% if member.github != 0 %}<a href="{{ member.github }}"><i class="fa fa-github"></i></a>{% endif %}
    {% if member.twitter != 0 %}<a href="{{ member.twitter }}"><i class="fa fa-twitter"></i></a>{% endif %}
  </div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}
{% if number_printed | modulo: 2 == 1 %}
</div>
{% endif %}
<br>

## PhDs
{% assign number_printed = 0 %}
{% for member in site.data.phd %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">
    {% for i in (1..member.number_educ) %}
    <li>{{ member["education" | append: i] }}</li>
    {% endfor %}
  </ul>
  <div class="social-links"> 
    {% if member.website != 0 %}<a href="{{ member.website }}"><i class="fa fa-link"></i></a>{% endif %}
    {% if member.linkedin != 0 %}<a href="{{ member.linkedin }}"><i class="fa fa-linkedin"></i></a>{% endif %}
    {% if member.github != 0 %}<a href="{{ member.github }}"><i class="fa fa-github"></i></a>{% endif %}
    {% if member.twitter != 0 %}<a href="{{ member.twitter }}"><i class="fa fa-twitter"></i></a>{% endif %}
  </div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}
{% if number_printed | modulo: 2 == 1 %}
</div>
{% endif %}
<br><br>

## Masters
{% assign number_printed = 0 %}
{% for member in site.data.ms %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">
    {% for i in (1..member.number_educ) %}
    <li>{{ member["education" | append: i] }}</li>
    {% endfor %}
  </ul>
  <div class="social-links"> 
    {% if member.website != 0 %}<a href="{{ member.website }}"><i class="fa fa-link"></i></a>{% endif %}
    {% if member.linkedin != 0 %}<a href="{{ member.linkedin }}"><i class="fa fa-linkedin"></i></a>{% endif %}
    {% if member.github != 0 %}<a href="{{ member.github }}"><i class="fa fa-github"></i></a>{% endif %}
  </div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}
{% if number_printed | modulo: 2 == 1 %}
</div>
{% endif %}
<br><br>

## Undergraduates
{% assign number_printed = 0 %}
{% for member in site.data.bs %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  <ul style="overflow: hidden">
    {% for i in (1..member.number_educ) %}
    <li>{{ member["education" | append: i] }}</li>
    {% endfor %}
  </ul>
  <div class="social-links"> 
    {% if member.linkedin != 0 %}<a href="{{ member.linkedin }}"><i class="fa fa-linkedin"></i></a>{% endif %}
    {% if member.github != 0 %}<a href="{{ member.github }}"><i class="fa fa-github"></i></a>{% endif %}
  </div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}
{% if number_printed | modulo: 2 == 1 %}
</div>
{% endif %}
<br><br>

## Interns
{% assign number_printed = 0 %}
{% for member in site.data.interns %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}{% if member.email %}<br>email: {{ member.email }}{% endif %}</i>
  <ul style="overflow: hidden">
    {% for i in (1..member.number_educ) %}
    <li>{{ member["education" | append: i] }}</li>
    {% endfor %}
  </ul>
  <div class="social-links"> 
    {% if member.website != 0 %}<a href="{{ member.website }}"><i class="fa fa-link"></i></a>{% endif %}
    {% if member.linkedin != 0 %}<a href="{{ member.linkedin }}"><i class="fa fa-linkedin"></i></a>{% endif %}
    {% if member.github != 0 %}<a href="{{ member.github }}"><i class="fa fa-github"></i></a>{% endif %}
    {% if member.twitter != 0 %}<a href="{{ member.twitter }}"><i class="fa fa-twitter"></i></a>{% endif %}
  </div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endfor %}
{% if number_printed | modulo: 2 == 1 %}
</div>
{% endif %}
<br><br>
