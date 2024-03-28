---
layout: archive
title: "📝 Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## 🌟*<u>Selected Paper</u>*🌟
1. **Wen, Zhuo**; Hai, Huang; Xinran, Gao; Xuecao, Li; Jianxi, Huang. [An Improved Approach of Winter Wheat Yield Estimation by Jointly Assimilating Remotely Sensed Leaf Area Index and Soil Moisture into the WOFOST Model](https://doi.org/10.3390/rs15071825). **Remote Sensing**, 2023; 15(7):1825.
{% assign citation = site.data.citations %}
{% if site.author.googlescholar %}
  <div class="wordwrap">Citations: </div> citations['publications']['OjcQtH4AAAAJ:qjMakFHDy7sC']['num_citations']
{% endif %}
   * This study aims to examine the accuracy of crop yield estimation through the joint assimilation of leaf area index (LAI) and soil moisture (SM) and to examine the scale effect between remotely sensed data and crop model simulations. [Download paper here](https://wenzhuo727.github.io/wen/files/remotesensing2023.pdf)
   * <img src='/wen/images/RS2023.jpg' width='500'>
1. **Wen, Zhuo**; Shibo, Fang; Xinran, Gao; Lei, Wang; Dong, Wu; Shaolong, Fu; Qingling, Wu; Jianxi, Huang. [Crop yield prediction using MODIS LAI, TIGGE weather forecasts and WOFOST model: A case study for winter wheat in Hebei, China during 2009–2013](https://doi.org/10.1016/j.jag.2021.102668). **International Journal of Applied Earth Observation and Geoinformation**, 2022; 106, 102668.
   * The objective of this study is to predict winter wheat yield at the regional scale and improve the accuracy by assimilating remotely sensed observations. [Download paper here](https://wenzhuo727.github.io/wen/files/JAG2021.pdf)
   * <img src='/wen/images/JAG20211.jpg'>
1. **Wen, Zhuo**; Jianxi, Huang; Xiangming, Xiao; Hai, Huang; Rajen, Bajgain; Xiaocui, Wu; Xinran, Gao; Jie, Wang; Xuecao, Li; Pradeep, Wagle. [Assimilating remote sensing-based VPM GPP into the WOFOST model for improving regional winter wheat yield estimation](https://doi.org/10.1016/j.eja.2022.126556). **European Journal of Agronomy**, 2022; 139(11), 126556.
   * In this study, a novel crop data-model assimilation framework was proposed that assimilates accumulative GPP estimates from the VPM model into the WOFOST model using EnKF algorithm to estimate winter wheat GPP and grain yield. [Download paper here](https://wenzhuo727.github.io/wen/files/EJA2022.pdf)
   * <img src='/wen/images/EJA2022.jpg' width='500' height='315'>
1. **Wen, Zhuo**; Shibo, Fang; Dong, Wu; Lei, Wang; Mengqian, Li; Jiansu, Zhang; Xinran, Gao. [Integrating remotely sensed water stress factor and crop growth model for winter wheat yield estimation in the North China Plain during 2008 to 2018](https://doi.org/10.1016/j.cj.2022.04.004). **Crop Journal**, 2022, 10, 1470–1482.
   * The objective of this study was to estimate winter wheat yield at the regional scale in the NCP, and to improve yield estimation accuracy by integrating remotely sensed water stress factor with the WOFOST model. [Download paper here](https://wenzhuo727.github.io/wen/files/CJ2022.pdf)
   * <img src='/wen/images/CJ2022.jpg' width='500' height='227'>

## ⭐*<u>All Paper List (18 peer-reviewed journal papers in total since 2018)</u>*⭐
_====Click the **article title** for more details ❗====_

{% include base_path %}

<ul>{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}</ul>
