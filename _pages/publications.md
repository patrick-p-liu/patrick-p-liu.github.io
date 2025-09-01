---
layout: page
permalink: /research/
title: research
description: # published papers and ongoing work by categories in reversed chronological order. 
nav: false
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

_Publications_

{% bibliography --query @*[keywords=publication] %}

_Working Papers (Drafts Available Upon Request)_

{% bibliography --query @*[keywords=working] %}

</div>
