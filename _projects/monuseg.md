---
layout: page
title: Multi-Organ Nuclei Segmentation
description: Winter project @ MeDAL, IIT Bombay
img: assets/img/monuseg.png
importance: 2
category: Research Projects
---

Guide: [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/)  
Code+Papers dump: [Winter2019](https://github.com/ipsitmantri/Winter2019)

- Trained a sliding window CNN and a UNet seperately, on over 22,000 hand annotated nuclei spanning 4 different organs
and tested them on three unseen organs for three classes in Pytorch on H&E stained images
- Implemented Structure-Preserving Color Normalization (SPCN) on WSIs using SNMF and SPAMS package  
![SPCN](/assets/img/spcn.png)
- Adopted iterative region growing to get n-ary Nuclear Maps and used Aggregated Jaccard-Index as accuracy metric
