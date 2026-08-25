---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/Betul_Ozturan.pdf" class="btn btn--large" target="_blank" rel="noopener">Download full CV (PDF)</a></p>

<div class="cv-embed">
  <object data="{{ base_path }}/files/Betul_Ozturan.pdf" type="application/pdf" width="100%" height="1200px">
    <p>Your browser can't display the CV inline. <a href="{{ base_path }}/files/Betul_Ozturan.pdf">Download the PDF</a> instead.</p>
  </object>
</div>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
