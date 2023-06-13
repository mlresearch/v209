---
title: Denoising Autoencoders for Learning from Noisy Patient-Reported Data
abstract: 'Healthcare datasets often include patient-reported values, such as mood,
  symptoms, and meals, which can be subject to varying levels of human error. Improving
  the accuracy of patient-reported data could help in several downstream tasks, such
  as remote patient monitoring.  In this study, we propose a novel denoising autoencoder
  (DAE) approach to denoise patient-reported data, drawing inspiration from recent
  work in computer vision. Our approach is based on the observation that noisy patient-reported
  data are often collected alongside higher fidelity data collected from wearable
  sensors. We leverage these auxiliary data to improve the accuracy of the patient-reported
  data. Our approach combines key ideas from DAEs with co-teaching to iteratively
  filter and learn from clean patient-reported samples. Applied to the task of recovering
  carbohydrate values for blood glucose management in diabetes, our approach reduces
  noise (MSE) in patient-reported carbohydrates from 72$g^2$ (95% CI: 54-93) to 18$g^2$
  (13-25), outperforming the best baseline (33$g^2$ (27-43)). Notably, our approach
  achieves strong performance with only access to patient-reported target values,
  making it applicable to many settings where ground truth data may be unavailable. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rubin-falcone23a
month: 0
tex_title: Denoising Autoencoders for Learning from Noisy Patient-Reported Data
firstpage: 393
lastpage: 409
page: 393-409
order: 393
cycles: false
bibtex_author: Rubin-Falcone, Harry and Lee, Joyce M. and Wiens, Jenna
author:
- given: Harry
  family: Rubin-Falcone
- given: Joyce M.
  family: Lee
- given: Jenna
  family: Wiens
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
pdf: https://proceedings.mlr.press/v209/rubin-falcone23a/rubin-falcone23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
