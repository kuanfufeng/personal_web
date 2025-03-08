---
title: "KF Feng - Publications"
layout: gridlay
excerpt: "KF Feng -- Publications."
sitemap: false
permalink: /publications/
---
<div markdown="0" class="cover-image-container" style="text-align: center; margin: 1px 0;">
<img src="{{ site.url }}{{ site.baseurl }}/images/cover/rainier.jpg" 
    alt="Cover Image" 
    style="width: 100%; max-height: 250px; object-fit: fill; border-radius: 1px;">
</div>

#### Publications
**You can find my abtracts and publications on [google scholar](https://scholar.google.com/citations?hl=en&authuser=1&user=cFcJgigAAAAJ).**
<br />

<!-- {% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
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

<p> &nbsp; </p> -->

#### Upcoming
- A decadal survey of the near-surface seismic velocity response to hydrological variations in Utah, United States <br />
<em> **KF Feng**, M Denolle, FC Lin, T van Dam (**under review**) </em><br />
<br />
- Investigating seismic attenuation across the Pacific Northwest of the United States using the ambient noise <br />
<em>**KF Feng**, M Denolle, Y Ni (**in prep.**) </em><br />


#### Full List of publications

{% for publi in site.data.publist %}

  - {{ publi.title }} [<em><a href="{{ publi.link.url }}">{{ publi.link.display }}</a><em>]
  <br /><em>{{ publi.authors }} </em>

{% endfor %}

<!-- {% for publi in site.data.publist %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }}</em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% if publi.news %}
    (<em> News:
    {% for news_item in publi.news %}
      <a href="{{ news_item.url }}">{{ news_item.name }}</a>{% if forloop.last == false %}, {% endif %}
    {% endfor %}
    </em>)
  {% endif %}
  <br /><br />
{% endfor %} -->
<br />

#### Thesis
<em>**Feng, Kuan-Fu**</em> (2022) Noise-based monitoring on crustal seismic velocity variations [<em>[PhD Dissertation](https://doi.org/10.6342/NTU202200093)<em>]<br />
<em>Advisor: Huang, Hsin-Hua<em> & <em>co-advisor: Wu, Yih-Min<em><br />

<em>**Feng, Kuan-Fu**</em> (2016) Investigating the uncertainty of time-dependent seismic velocity changes using travel time tomography: a case study of the ML 6.4 2013 Rueisuei earthquake, Taiwan (2016) [<em>[Master Thesis](https://doi.org/10.6342/NTU201601358)<em>]<br />
<em>Advisor: Wu, Yih-Min<em>