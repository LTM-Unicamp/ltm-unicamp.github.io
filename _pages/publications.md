---
title: "LTM - Publications"
layout: gridlay
excerpt: "LTM -- Publications."
sitemap: false
permalink: /publications/
---


# Publications
**The [full list of publications](#full-list-of-publications) is at the end of the page.** 

---

## Group highlights
{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/ltm_publication/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p> Published in {{ publi.journal }}</p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news }}</strong></p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

<!--
## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a>

-->
## Full List of publications
---

{% assign pub = site.data.publist | where: "type", "paper" %}
<h3>Scientific Journal Papers</h3>
{% for publi in pub %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  Published in {{publi.journal}}, {{publi.year}} <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endfor %}


{% assign pub = site.data.publist | where: "type", "book" %}
<h3>Book Chapters</h3>
{% for publi in pub %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  Published in {{publi.journal}}, {{publi.year}} <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endfor %}


{% assign pub = site.data.publist | where: "type", "conference" %}
<h3>Papers Published in Annals of Events</h3>
{% for publi in pub %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  Published in {{publi.journal}}, {{publi.year}} <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endfor %}




<!--
{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  Published in {{publi.journal}}, {{publi.year}} <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
-->

<!--
{% assign pub = site.data.publist | where: "year", "2023" %}
<h4>2023</h4>
{% for publi in pub %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  Published in {{publi.journal}}, {{publi.year}} <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endfor %}
-->

<!--
{% for publi in site.data.publist %}
{% if publi.year == "2023" %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  Published in {{publi.journal}}, {{publi.year}} <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}
-->


