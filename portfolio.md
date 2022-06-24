---
layout: page
title: Portfolio
permalink: /portfolio/
collection: portfolio
published: true
---

Here are some of the projects I have worked on either alone or in collaboration with some of the most amazing people!

## [Correlation of crime with physical environment](https://github.com/SD-Suman/SD-Suman.github.io/blob/master/portfolio/2022-06-24-first-post.md)

This was my bachelor's thesis project. I have selectively shown only the most important information without the bulk of unnecessary information I may have used as a young bachelors student who did not know much about anything (I still don't know much - but it is a little better than before).


{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
