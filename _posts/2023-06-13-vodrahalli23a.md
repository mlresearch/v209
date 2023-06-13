---
title: Understanding and Predicting the Effect of Environmental Factors on People
  with Type 2 Diabetes
abstract: Type 2 diabetes mellitus (T2D) affects over 530 million people globally
  and is often difficult to manage leading to serious health complications. Continuous
  glucose monitoring (CGM) can help people with T2D to monitor and manage the disease.
  CGM devices sample an individual’s glucose level at frequent intervals enabling
  sophisticated characterization of an individual’s health. In this work, we leverage
  a large dataset of CGM data (5,447 individuals and 940,663 days of data) paired
  with health records and activity data to investigate how glucose levels in people
  with T2D are affected by external factors like weather conditions, extreme weather
  events, and temporal events including local holidays. We find temperature (p=$2.37\times10^{-8}$,
  n=3561), holidays (p=$2.23\times10^{-46}$, n=4079), and weekends (p=$7.64\times10^{-124}$,
  n=5429) each have a significant effect on standard glycemic metrics at a population
  level. Moreover, we show that we can predict whether an individual will be significantly
  affected by a (potentially unobserved) external event using only demographic information
  and a few days of CGM and activity data. Using random forest classifiers, we can
  predict whether an individual will be more negatively affected than a typical individual
  with T2D by a given external factor with respect to a given glycemic metric. We
  find performance (measured as ROC-AUC) is consistently above chance (across classifiers,
  median ROC-AUC=0.63). Performance is highest for classifiers predicting the effect
  of time-in-range (median ROC-AUC=0.70). These are important findings because they
  may enable better patient care management with day-to-day risk assessments based
  on external factors as well as improve algorithm development by reducing train-
  and test-time bias due to external factors.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vodrahalli23a
month: 0
tex_title: Understanding and Predicting the Effect of Environmental Factors on People
  with Type 2 Diabetes
firstpage: 545
lastpage: 555
page: 545-555
order: 545
cycles: false
bibtex_author: Vodrahalli, Kailas and Lyng, Gregory D and Hill, Brian L and Karkkainen,
  Kimmo and Hertzberg, Jeffrey and Zou, James and Halperin, Eran
author:
- given: Kailas
  family: Vodrahalli
- given: Gregory D
  family: Lyng
- given: Brian L
  family: Hill
- given: Kimmo
  family: Karkkainen
- given: Jeffrey
  family: Hertzberg
- given: James
  family: Zou
- given: Eran
  family: Halperin
date: 2023-06-13
address:
container-title: Proceedings of the Conference on Health, Inference, and Learning
volume: '209'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 6
  - 13
pdf: https://proceedings.mlr.press/v209/vodrahalli23a/vodrahalli23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v209/vodrahalli23a/vodrahalli23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
