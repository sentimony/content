---
layout: default
permalink: /releases/micro/
title: 'releases:micro'
description: 'releases:micro'
og-image: ''
---

# {{ page.title }}

{% include menu-releases.html %}

<section>
  {% for file in site.static_files reversed %}
    {% if file.path contains 'assets/img/releases/micro/' %}
      {% include article.html %}
    {% endif %}
  {% endfor %}
</section>
