---
title: "Water detection leakage"
collection: projects
permalink: /projects/2025-water-detection-leakage/
---

The objective of this academic work is to develop an artificial intelligence model capable of detecting leaks within a water distribution operator’s network using historical data collected from water meters.

- [Github - Water detection leakage](https://github.com/nd-serge/water-leakage-detection)
- [Technical report - Water detection leakage](https://drive.google.com/file/d/1IdxNkuK894EMn-qzCBB0AuwmM0vEUSvC/view?usp=drive_link)
- Co-author [Aurore Fohoundi](mailto:fohoundibehiblo@gmail.com)

### Context
---
<div style="text-align: justify;">

In this academic project, we focused on detecting leaks in the network of a local public water distribution operator, which supplies tens of millions of cubic meters of potable water to thousands of households, businesses, and communities. The distribution network is highly vulnerable to leaks, which can represent 20 to 25% of the water supplied in certain areas.
</div>

### Methodology
---
<div style="text-align: justify;">
The proposed approach for leak detection is based on analyzing active consumption values combined with the components obtained from time series decomposition, namely trend, seasonality, and residuals.
</div>

### Result
--- 
<div style="text-align: justify;">

The baseline data filtering approach excludes extreme values from the consumption distribution, considering observations between the 10th and 90th percentiles as normal. Values outside this range are treated as potential leaks, allowing the detection of small variations in consumption.

The DBSCAN algorithm clusters data based on neighborhood density and core points, effectively identifying significant consumption variations and anomalies.

The Isolation Forest algorithm detects anomalies by isolating data points using random decision trees. While effective for larger deviations, it is less sensitive to minor variations in consumption.
</div>


