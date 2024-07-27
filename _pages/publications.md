---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
---

<div class="publications">
  <div class="table-responsive">
    <table class="table table-sm table-borderless">
    {% assign publications = site.publications | sort: 'date' | reverse %}
    {% for publi in publications %}
      {% if publi.show %}
        {% include publication.html %}
      {% endif %}
    {% endfor %}
    </table>
  </div>
