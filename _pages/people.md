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
  <h4>{% if member.website and member.website != 0 and member.website != "" %}<a href="{{ member.website }}">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</h4>
  <i>{{ member.info }} <br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links">
  {% if member.scholar != 0 %} <a href="{{ member.scholar }}"> <i class="fa fa-scholar"></i></a> {% endif %} {% if member.linkedin != 0 %} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %} {% if member.github != 0 %} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %} {% if member.twitter != 0 %} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %}
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

{% if member.group_heading %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% assign number_printed = 0 %}
<h3>{{ member.group_heading }}</h3>
{% endif %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{% if member.website and member.website != 0 and member.website != "" %}<a href="{{ member.website }}">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</h4>

  <i>{{ member.info }} <br>email: {{ member.email }}{% if member.co_advised_by %}<br>{{ member.co_advised_by }}{% endif %}</i>
  <ul style="overflow: hidden">

  {% if member.research_direction %}
  <li> Direction: {{ member.research_direction }} </li>
  <li> 1st Author Research Outcomes:
    <ul>
    {% for outcome in member.research_outcomes %}
      <li>{{ outcome }}</li>
    {% endfor %}
    </ul>
  </li>
  {% if member.achievements %}
  <li> Achievements:
    <ul>
    {% for achievement in member.achievements %}
      <li>{{ achievement }}</li>
    {% endfor %}
    </ul>
  </li>
  {% endif %}
  {% else %}
  {% if member.number_educ == 0 %}
  {% endif %}

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  {% endif %}

  </ul>
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
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{% if member.website and member.website != 0 and member.website != "" %}<a href="{{ member.website }}">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</h4>
  <i>{{ member.info }}  <br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">
  {% if member.research_direction %}
  <li> Direction: {{ member.research_direction }} </li>
  {% endif %}
  {% if member.achievements %}
  <li> Achievements:
    <ul>
    {% for achievement in member.achievements %}
      <li>{{ achievement }}</li>
    {% endfor %}
    </ul>
  </li>
  {% endif %}
  {% if member.next_position %}
  <li> Next Position: {{ member.next_position }} </li>
  {% endif %}
  {% unless member.research_direction or member.achievements or member.next_position %}
  {% if member.number_educ == 0 %}
  {% endif %}
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
  {% endunless %}
  </ul>
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
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{% if member.website and member.website != 0 and member.website != "" %}<a href="{{ member.website }}">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</h4>
  <i>{{ member.info }}</i>  <!-- <br>email: {{ member.email }} -->
  <ul style="overflow: hidden">

  {% if member.research_direction %}
  <li> Direction: {{ member.research_direction }} </li>
  {% endif %}
  {% if member.achievements %}
  <li> Achievements:
    <ul>
    {% for achievement in member.achievements %}
      <li>{{ achievement }}</li>
    {% endfor %}
    </ul>
  </li>
  {% endif %}
  {% if member.next_position %}
  <li> Next Position: {{ member.next_position }} </li>
  {% endif %}
  {% unless member.research_direction or member.achievements or member.next_position %}
  {% if member.number_educ == 0 %}
  {% endif %}

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  {% endunless %}

  </ul>


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




## High School Students
{% assign number_printed = 0 %}
{% for member in site.data.hs %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{% if member.website and member.website != 0 and member.website != "" %}<a href="{{ member.website }}">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</h4>
  <i>{{ member.info }}</i>
  <ul style="overflow: hidden">
  {% if member.research_direction %}
  <li> Direction: {{ member.research_direction }} </li>
  {% endif %}
  {% if member.achievements %}
  <li> Achievements:
    <ul>
    {% for achievement in member.achievements %}
      <li>{{ achievement }}</li>
    {% endfor %}
    </ul>
  </li>
  {% endif %}
  {% unless member.research_direction or member.achievements %}
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  {% endunless %}
  </ul>
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
