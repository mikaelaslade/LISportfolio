---
title: Home
layout: default
permalink: /
---
This website will function as an e-portfolio for Mikaela Slade for the purposes of showcasing her individual skills gained through Dominican University’s MLIS program.

Full guidelines for the e-portfolio requirements can be found [here](https://www.dom.edu/sites/default/files/pdfs/GRAD_Academic-Programs/SOIS/ePortfolioGuidelinesRubric2017-MLIS-LIS890.pdf).

{% for subgoal_page in site.subgoal_pages %}
  {{ subgoal_page.title }}
  {{ subgoal_page.content | truncatewords: 5, '...' }}

{% endfor %}
