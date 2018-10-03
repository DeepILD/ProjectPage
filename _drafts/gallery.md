---
layout: page
title: Code
subtitle: From the pexels folder
permalink: /code/
gallery_path: "assets/img/pexels"
tags: [Engineering, Code]
menu_order: 4
---

This is a photo gallery made from the static files in the `assets/img/pexels` folder. 
I wanted to create automatically a simple gallery from a folder without having to create a markdown page as you would for the portfolio.


{% include gallery.html gallery_path=page.gallery_path %}