---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here are my publications:

# Journal
1. **Long Pan**, E.O.D. Waygood, Zachary Patterson (2022). Would You Wait? Bus Choice Behavior Analysis Considering Various Incentives. Transportation Research Record.
1. **Long Pan**, Enjian Yao, Yang Yang, Rui Zhang (2020). A location model for electric vehicle (EV) public charging stations based on drivers’ existing activities. Sustainable Cities and Society, 59, 102192.
1. **Long Pan**, Enjian Yao, Don MacKenzie (2019). Modeling EV charging choice considering risk attitudes and attribute non-attendance. Transportation Research Part C: Emerging Technologies.
4. **Long Pan**, Enjian Yao, Don MacKenzie, Rui Zhang (2019). Environmental Effects of BEV Penetration Considering Traffic Status. Journal of Transportation Engineering, Part A: Systems, 145(11), 04019048. (Selected as Editor's Choice in Nov. 2019)
5. **Long Pan**, Enjian Yao, Yang Yang (2016). Impact analysis of traffic-related air pollution based on real-time traffic and basic meteorological information. Journal of Environmental Management, 183, 510-520.










# Conference paper

# Book chapter


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
