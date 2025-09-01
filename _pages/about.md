---
layout: about
title: Home
permalink: /
subtitle: 

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p style="font-size:14px">PhD Candidate</p>
    <p style="font-size:14px">Department of Political Science</p>
    <p style="font-size:14px"><a href='https://polisci.columbia.edu/'>Columbia University</a></p>

selected_papers: # includes a list of papers marked as "selected={true}"
social: # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit:  # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! I am a PhD Candidate in Political Science at Columbia University. My research aims to disentangle the conditions under which political attitudes undergo lasting change.

Much of my work uses tailored experimental designs to assess how canonical theories in political psychology—from motivated reasoning to models of attitudes as weighted sums of beliefs—hold up when we account for heterogeneity in the issues to which ordinary people assign importance or in the kinds of information they treat as relevant to their deeply held views. I also examine how social pressure constrains political conversation in underappreciated contexts such as intra-party dyads. 

My work is featured in the _American Political Science Review_ and has been supported by the Civic Health and Institutions Project, Columbia's Office of the Provost, and the Columbia Experimental Laboratory for Social Sciences.

## Publications

<!-- _pages/publications.md -->
<div class="publications">
{% bibliography --query @*[keywords=publication] %}
</div>

## Working Papers (Drafts Available Upon Request)

<!-- _pages/publications.md -->
<div class="publications">
{% bibliography --query @*[keywords=working] %}
</div>

## Ongoing Projects

<!-- _pages/publications.md -->
<div class="publications">
{% bibliography --query @*[keywords=ongoing] %}
</div>
