---
title: "Thrips detection (Cap2020)"
collection: projects
permalink: /projects/2026-thrips-detection/
---

Study conducted as part of AI4Industry 2026, focusing on the analysis of the impact of controlled noise on improving the detection of insects known as thrips. 

- [Github - Thrips detection (Cap2020)](https://github.com/nd-serge/cap-2020-thrips-detection)
- [Technical report - Thrips detection (Cap2020)](https://docs.google.com/document/d/1gUzqBPO2yHDqBXtblRELpFFJBjkiiHDIHXM8d9Ysqlg/edit?usp=sharing)

### Problem Statement
---
<div style="text-align: justify;">

Can image quality be improved, for example, by adding noise to high-quality images?
</div>


### Methodology
---
<div style="text-align: justify;">
To augment the dataset, controlled noise was applied to high-quality images using several noise models. Gaussian noise was introduced as additive noise following a normal distribution with a mean of 0 and a variance of 0.01. Poisson noise was applied as additive noise correlated with the intensity of each pixel. Salt-and-pepper noise was used as impulsive noise, randomly affecting between 5% and 40% of the image pixels.
</div>


### Result
--- 
<div style="text-align: justify;">

At the end of the study, we observed that data augmentation through the controlled introduction of noise into high-quality images has a progressive impact on the F1-score of the thrips detection model.

</div>


