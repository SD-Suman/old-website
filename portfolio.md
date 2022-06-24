---
layout: page
title: Portfolio
permalink: /_portfolio/
published: true
---


### Portfolio of Projects

Below are some of my projects created by me or in collaboration with amazing people!


<!--

---
layout: default
title: "Portfolio"
permalink: /portfolio/
collection: portfolio
author_profile: true
---
-->


<!--
## [Climate Proofing Cities: A Resilience Analysis](https://anamika255.github.io/portfolio/C40-Cities/)

100 climate proofing strategies were implemented by the global consortium of C40 cities. How did those strategies fare on a resilience landscape?
Here's how to add link to the pages (/assets/files/C40_report.pdf)

### Other projects coming up soon.
-->

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
