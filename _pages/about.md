---
layout: about
title: Home
permalink: /
subtitle: 

profile:
  align: left
  image: prof_web_resized.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p style="font-size:16px; font-family:Roboto">PhD Candidate</p>
    <p style="font-size:16px; font-family:Roboto">Department of Political Science</p>
    <p style="font-size:16px; font-family:Roboto"><a href='https://polisci.columbia.edu/'>Columbia University</a></p>
    <p style="font-size:16px; font-family:Roboto; margin-top:0.5rem"><a href='mailto:ppl2115@columbia.edu'><i class="ti ti-mail" style="vertical-align: middle; margin-right: 0.25rem"></i>ppl2115@columbia.edu</a></p>
    <p style="margin-top:0.5rem"><a href="assets/pdf/Liu_Vitae.pdf" style="font-size:16px; font-family:Roboto"><i class="ai ai-cv ai-1x" style="vertical-align: middle; margin-right: 0.25rem"></i>Curriculum Vitae</a></p>

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

I am a PhD candidate in political science at Columbia University. My work aims to disentangle the conditions under which political attitudes undergo lasting change.

My current research centers on (i) a synthesis of theoretical explanations and empirical evidence for decay in belief and attitude change, and (ii) understanding if and when personal policy experiences shape party evaluations and electoral behavior. This includes evaluating the policy feedback effects of Biden-era student loan forgiveness and its impact on borrowers' 2024 election behavior. My published papers use novel experimental designs—leveraging large language models to tailor stimuli and outcomes on-the-fly—to reevaluate canonical theories in public opinion and political psychology and to assess the persuasive returns from personalization. Other research interests include social influence, partisan identity, and voter responses to democratic backsliding.

My work is featured in the _American Political Science Review_ and has been supported by the Rapoport Family Foundation, the Columbia Center for Political Economy, the Civic Health and Institutions Project, the Institute for Humane Studies, the Columbia Experimental Laboratory for Social Sciences, and the Office of the Provost.


#### Publications

<div class="publications">
{% bibliography --query @*[keywords=publication] %}
</div>

#### Under Review

<div class="publications">
{% bibliography --query @*[keywords=working] %}
</div>

#### Works in Progress

<div class="publications">
{% bibliography --query @*[keywords=ongoing] %}
</div>
