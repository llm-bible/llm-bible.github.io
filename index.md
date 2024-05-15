---
layout: default
title: A Comprehensive Overview of Large Language Models (LLMs) with Papers, Resources and Colab Notebooks
---
### Welcome to the LLM Bible!

Large Language Models (LLMs) represent a groundbreaking leap in artificial intelligence, enabling machines to interpret, generate, and engage with human language in ways that are both profound and transformative. These models, trained on diverse datasets containing trillions of words, have become the backbone of numerous applications that influence how we gather information, make decisions, and interact with technology.

This website is dedicated to exploring the fascinating world of LLMs. Here, you will find a curated collection of research papers, Colab Notebooks, and educational materials to learn about LLMs. 

#### 🏷 Browse Papers by Tag
{% assign rawtags = Array.new %}
{% for publication in site.publications %}
  {% assign ttags = publication.tags  %}  
  {% assign rawtags = rawtags | concat: ttags %}  
{% endfor %}
{% assign rawtags = rawtags | uniq | sort_natural %}
{% for tag in rawtags %}<tag><a href="/tags.html#{{ tag }}">{{ tag }}</a></tag> {% endfor %}

### About This Site

This site is an experiment: a [living literature review](https://en.wikipedia.org/wiki/Living_review) that allows
you explore, [search and navigate]({% link papers.html %}) the literature in this area.

### Contributing

This research area is evolving so fast that a static review cannot keep up.
But a website can! We hope to make this site a living document.
Anyone can add a paper to this web site, by completing a simple [web form](contributing.html).

### Contributors

The core survey and the original taxonomy was created by

* [Sean Moran](https://sjmoran.github.io)

#### Contributors to the website
This website accepts external [contributions](/contributing.html).
Please, feel free to add your name below, once you contribute to this
website. A comprehensive list can be found [here](https://github.com/ml4code/ml4code.github.io/graphs/contributors).

Copyright © Sean Moran 2024. All opinions are my own.
