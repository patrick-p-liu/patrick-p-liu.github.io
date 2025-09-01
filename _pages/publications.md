---
layout: page
permalink: /research/
title: research
description: # published papers and ongoing work by categories in reversed chronological order. 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

## Publications
{% bibliography --query @*[keywords=publication] %}

## Working Papers
{% bibliography --query @*[keywords=working] %}

</div>
