---
title: "RDCRMG: A raster dataset clean & reconstitution multi-grid architecture for remote sensing monitoring of vegetation dryness"
collection: publications
permalink: /publication/RDCRMG A raster dataset clean & reconstitution multi-grid architecture for remote sensing monitoring of vegetation dryness
excerpt: 'This paper reports on a Raster Dataset Clean & Reconstitution Multi-Grid (RDCRMG) architecture for remote sensing monitoring of vegetation dryness in which different types of raster datasets have been partitioned, organized and systematically applied.'
date: 2018-08-30
venue: 'Remote Sensing'
paperurl: 'https://doi.org/10.3390/rs10091376'
citation: Sijing, Ye; Diyou, Liu; Xiaochuang, Yao; Huaizhi, Tang; Quan, Xiong; Wen, Zhuo; Zhenbo, Du; Jianxi, Huang; Wei, Su; Shi, Shen; Zuliang, Zhao; Shaolong, Cui; Lixin, Ning; Dehai, Zhu; Changxiu, Cheng; Changqing, Song. RDCRMG A raster dataset clean & reconstitution multi-grid architecture for remote sensing monitoring of vegetation dryness. Remote Sensing, 2018, 10, 1376. 
---

## Abstract
In recent years, remote sensing (RS) research on crop growth status monitoring has gradually turned from static spectrum information retrieval in large-scale to meso-scale or micro-scale, timely multi-source data cooperative analysis; this change has presented higher requirements for RS data acquisition and analysis efficiency. How to implement rapid and stable massive RS data extraction and analysis becomes a serious problem. This paper reports on a Raster Dataset Clean & Reconstitution Multi-Grid (RDCRMG) architecture for remote sensing monitoring of vegetation dryness in which different types of raster datasets have been partitioned, organized and systematically applied. First, raster images have been subdivided into several independent blocks and distributed for storage in different data nodes by using the multi-grid as a consistent partition unit. Second, the “no metadata model” ideology has been referenced so that targets raster data can be speedily extracted by directly calculating the data storage path without retrieving metadata records; third, grids that cover the query range can be easily assessed. This assessment allows the query task to be easily split into several sub-tasks and executed in parallel by grouping these grids. Our RDCRMG-based change detection of the spectral reflectance information test and the data extraction efficiency comparative test shows that the RDCRMG is reliable for vegetation dryness monitoring with a slight reflectance information distortion and consistent percentage histograms. Furthermore, the RDCGMG-based data extraction in parallel circumstances has the advantages of high efficiency and excellent stability compared to that of the RDCGMG-based data extraction in serial circumstances and traditional data extraction. At last, an RDCRMG-based vegetation dryness monitoring platform (VDMP) has been constructed to apply RS data inversion in vegetation dryness monitoring. Through actual applications, the RDCRMG architecture is proven to be appropriate for timely vegetation dryness RS automatic monitoring with better performance, more reliability and higher extensibility. Our future works will focus on integrating more kinds of continuously updated RS data into the RDCRMG-based VDMP and integrating more multi-source datasets based collaborative analysis models for agricultural monitoring.

## Key words
big data; remote sensing; vegetation dryness; multi-grid; architecture

[Download paper here](https://wenzhuo727.github.io/wen/files/remotesensing2018.pdf)



