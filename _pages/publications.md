---
layout: archive
title: "📝 Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## Selected Paper 
* **Wen, Zhuo**; Hai, Huang; Xinran, Gao; Xuecao, Li; Jianxi, Huang*. An Improved Approach of Winter Wheat Yield Estimation by Jointly Assimilating Remotely Sensed Leaf Area Index and Soil Moisture into the WOFOST Model. **Remote Sensing**, 2023; 15(7):1825.
  * <br/><br/><img src='/wen/images/RS2023.jpg' width='500'>
* fjsla
* adjk

## All Paper List
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
