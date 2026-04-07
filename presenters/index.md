---
title: More About the Presenters
layout: base
---

# More About the Presenters

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'presenters/'" | where_exp: "p", "p.path != 'presenters/index.md'" %}

{% include nav/card-toc.html rows=cards %}





<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">


