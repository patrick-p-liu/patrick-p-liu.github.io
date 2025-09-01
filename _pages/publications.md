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
{% bibliography --file papers --query @*[keywords=publication] %}

## Working Papers
{% bibliography --file papers --query @*[keywords=working] %}

## Drafts in Progress
{% bibliography --file papers --query @*[keywords=draft] %}

</div>
