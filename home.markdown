---
title: Home
date: 2016-12-26 17:12:00 Z
permalink: "/"
position: 0
is hidden from nav: true
header: ONLY 5 UNITS LEFT
call to action:
  header: SEE AVAILABLE FLOORPLANS
  page url: "/floor-plans"
  image: "/uploads/hero2-compressor.png"
Field name: 
layout: default
---

<div class="hero-image">
  <div class="hero-image__image-container">
    <img src="{{ page["call to action"].image }}" alt="stock photo">
    <div class="hero-image__overlay"></div>
  </div>
  <div class="wrapper">
    <div class="hero-image__cta">
      <h1 class="hero-image__cta-header">
        {{ page.header }}
      </h1>
      <a class="hero-image__cta-link" href="{{ page["call to action"]["page url"] }}">
        {{ page["call to action"].header }}
      </a>
  </div>
</div>