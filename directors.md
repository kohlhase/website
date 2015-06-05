---
layout: page
title: Board of Directors
directors:
- name: Deyan Ginev
  description: Deyan Ginev is pursuing a PhD in Computer Science at Jacobs University Bremen, with a focus on semantic enrichment of TeX formulas into Content MathML. He is also a core developer for LaTeXML, Authorea and PlanetMath.
  photo: img/people/ginev.deyan.jpg
- name: Michael Kohlhase
  description: Dr. Michael Kohlhase is professor for Computer Science at Jacobs University Bremen. His research interests range from automated reasoning to eLearning via natural language semantics and the Semantic Web.
  photo: img/people/kohlhase.michael.jpg
- name: Moritz Schubotz
  description: Moritz Schubotz alias Physikerwelt is research associate at Technische Universität Berlin. His research vision is to find instantiations of mathematical concepts independent of the concrete representation in huge corpora of human readable documents.
  photo: img/people/schubotz.moritz.jpg
- name: Raniere Silva
  description: MathML enthusiastic and interested in MathML native support in web browsers and EPUB reader.
  photo: img/people/silva.raniere.jpg

- name: Frédéric Wang
  description: Frédéric Wang has been involved in math-on-the-web projects for several years, including MathML implementations of web rendering engines. He holds a master degree in pure mathematics and an engineer's degree in computer science.
  photo: img/people/wang.frederic.jpg
---

{% for people in page.directors %}
<div class="people">
<div class="people-photo">
{%if people.photo %}
<img src="{{people.photo}}">
{% endif %}
</div>
<div class="people-info">
<p><strong>{{people.name}}</strong></p>
<p>{{people.description}}</p>
</div>
</div>
{% endfor %}