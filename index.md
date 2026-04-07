---
title: "GRAD SHOWCASE FOR GENDER WORKS-IN-PROGRESS"
layout: base
date: 2026-04-07
header-image: "/assets/images/grad-showcase-header.png"
header-title: Grad Showcase for Gender Works-in-Progress
header-subtitle: Hosted by the Department of History, the History Graduate Student Association, and the Women, Gender, and Sexuality Studies Program (WGSS) 
header-position: 35% center
---

# Grad Showcase for Gender Works-in-Progress

This is your class project site, built with the [Xanthan framework](https://xanthan-web.github.io/xanthan/). Everything you see here is a placeholder — the title above, the essay topics, the images. Your course topic and your students' writing go here.

To get a sense of what a finished project can look like, this template includes three sample essays on Southwest food history, generated with AI as stand-ins for real student work. Browse them to see how essays can use images, pull quotes, and scroll-driven backgrounds. Then start replacing them with your own material.

**Ready to begin?** Open `index.md` in your editor and change the title and this introduction. That's your first edit. The [documentation](docs/) covers everything else — how to add pages, configure navigation, set up student contributors, and customize the look.

The card grid below links to the sample essays. The info on these cards come from the essay pages themselves. As students publish their essaysm, these will showcase students' work as the project develops.

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}

