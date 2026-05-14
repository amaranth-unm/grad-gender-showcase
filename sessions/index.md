---
title: Sessions
layout: base
header-image: "/assets/images/grad-showcase-header-2.png"
header-height: 10vh
---

# Sessions

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'sessions/'" | where_exp: "p", "p.path != 'sessions/index.md'" %}

{% include nav/card-toc.html rows=cards %}





