---
title: Presenters
layout: base
---

# Presenters

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'presenters/'" | where_exp: "p", "p.path != 'presenters/index.md'" %}

{% include nav/card-grid.html cards=cards %}

<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">
<br style="clear: both">

---

*This site was built with the [Xanthan framework](https://xanthan-web.github.io/xanthan/), a free, open-source toolkit for academic websites hosted on GitHub Pages.*
