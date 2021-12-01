---
layout: archive
permalink: k8s
title: "k8s"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.k8s %}
{% for post in posts %}
  {% include custom-archive-single.html type=entries_layout %}
{% endfor %}