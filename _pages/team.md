---
title: "LTM - Team"
layout: gridlay
excerpt: "LTM -- Team"
sitemap: false
permalink: /team/
---

# Group Members
The LTM team is formed by undergraduate students, engineers (Post-docs, PhDs, MSc) and professors. Jump to [Full-Time Researchers](#full-time-researchers), [Part-Time Researchers](#part-time-researchers) or [Alumni](#alumni) to know more.

## Full-Time Researchers
{% assign number_printed = 0 %}
{% for member in site.data.staff_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/ltm_team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>
    {{ member.info }} <br>
    <a href="{{ member.lattes }}">Lattes</a> | <{{ member.email }}> <br>
  </i>
  <ul>
  {% if member.number_socials == 0 %}
     
  {% elsif member.number_socials == 1 %}
    <i><a href="{{ member.orcid }}">ORCID</a></i>
  {% elsif member.number_socials == 2 %}
    <i><a href="{{ member.orcid }}">ORCID</a></i> | <i><a href="{{ member.linkedin }}">LinkedIn</a></i> <br>
  {% endif %}
  </ul>
  <ul style="overflow: hidden">
  {% if member.number_educ == 0 %}
  
  {% elsif member.number_educ == 1 %}
    <li> {{ member.education1 }} </li>
  {% elsif member.number_educ == 2 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
  {% elsif member.number_educ == 3 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
  {% elsif member.number_educ == 4 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
    <li> {{ member.education4 }} </li>
  {% elsif member.number_educ == 5 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
    <li> {{ member.education4 }} </li>
    <li> {{ member.education5 }} </li>
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


---
## Part-Time Researchers
{% assign number_printed = 0 %}
{% for member in site.data.partime_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/ltm_team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>
    {{ member.info }} <br>
    <a href="{{ member.lattes }}">Lattes</a> | <{{ member.email }}> <br>
  </i>
  <ul>
  {% if member.number_socials == 0 %}
     
  {% elsif member.number_socials == 1 %}
    <i><a href="{{ member.orcid }}">ORCID</a></i>
  {% elsif member.number_socials == 2 %}
    <i><a href="{{ member.orcid }}">ORCID</a></i> | <i><a href="{{ member.linkedin }}">LinkedIn</a></i> <br>
  {% endif %}
  </ul>
  <ul style="overflow: hidden">
  {% if member.number_educ == 0 %}
  
  {% elsif member.number_educ == 1 %}
    <li> {{ member.education1 }} </li>
  {% elsif member.number_educ == 2 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
  {% elsif member.number_educ == 3 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
  {% elsif member.number_educ == 4 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
    <li> {{ member.education4 }} </li>
  {% elsif member.number_educ == 5 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
    <li> {{ member.education4 }} </li>
    <li> {{ member.education5 }} </li>
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



---
## Alumni
{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/ltm_team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>
    {{ member.info }} <br>
    <a href="{{ member.lattes }}">Lattes</a> | <{{ member.email }}> <br>
  </i>
  <ul>
  {% if member.number_socials == 0 %}
     
  {% elsif member.number_socials == 1 %}
    <i><a href="{{ member.orcid }}">ORCID</a></i>
  {% elsif member.number_socials == 2 %}
    <i><a href="{{ member.orcid }}">ORCID</a></i> | <i><a href="{{ member.linkedin }}">LinkedIn</a></i> <br>
  {% endif %}
  </ul>
  <ul style="overflow: hidden">
  {% if member.number_educ == 0 %}
  
  {% elsif member.number_educ == 1 %}
    <li> {{ member.education1 }} </li>
  {% elsif member.number_educ == 2 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
  {% elsif member.number_educ == 3 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
  {% elsif member.number_educ == 4 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
    <li> {{ member.education4 }} </li>
  {% elsif member.number_educ == 5 %}
    <li> {{ member.education1 }} </li>
    <li> {{ member.education2 }} </li>
    <li> {{ member.education3 }} </li>
    <li> {{ member.education4 }} </li>
    <li> {{ member.education5 }} </li>
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
