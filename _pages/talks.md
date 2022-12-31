---
title: "Invited Talks"
permalink: /talks/
author_profile: true
---

My most recent academic talks focus on my current research on patient expertise and the co-production of medical knowledge online. Outside academia, my talks have engaged industry and community stakeholders to think critically about ethics in AI and the impact of digital health on the wellbeing of patients and communities.  

## Industry Talks  

*Artificial Intelligence: A Balancing Act Between Business Growth and Fairness*  
13 July 2022  
BT "Never Stop Learning" Event (UK)  

*Digital Health*  
23 November 2021
Raymond Nicolet Trust [Podcast](https://www.youtube.com/watch?v=bTqXZvDHd3A)  





{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
