---
title: "Firewall CPU consumption prediction"
collection: projects
permalink: /projects/2024-firewall-cpu-prediction/
---
<div style="text-align: justify;">
This study presents a framework for monitoring and predicting CPU usage of a virtualized firewall deployed in a software-defined networking (SDN) environment within a Campus Area Network (CAN). </div>

- [Gitlab - Firewall CPU prediction](https://gitlab.com/nd.serge/cpu-firewall-prediction)
- [Technical report - Firewall CPU prediction](https://docs.google.com/document/d/1JWyKn1nFlgb15ulQhBNkx2hDr1Cs0KM4lMkolnBF6l0/edit?usp=sharing)
- Co-author [Darlene Nyangono](mailto:nyangonodarlene@gmail.com)

### Context
---
<div style="text-align: justify;">

In Campus Area Networks (CANs), virtualized network functions (VNFs) such as firewalls play a critical role in security and traffic management. Ensuring their efficient operation requires careful monitoring of resource usage, particularly CPU consumption, to maintain network performance and prevent overloads. This project proposes a framework to collect CPU usage data from a virtualized firewall deployed in a software-defined networking (SDN) environment using Mininet, and leverages these data to develop a hybrid method for predicting CPU resource requirements.
</div>

### Methodology
---
<div style="text-align: justify;">
Using the data collected from Knowledge Defined Networking (KDN), we explored models including Random Forest, Support Vector Regression (SVR), and LSTM for CPU prediction, incorporating preprocessing, data cleaning, and model optimization.
</div>

### Result
--- 
<div style="text-align: justify;">

This analysis highlights the effectiveness of Random Forest as the primary algorithm and as a feature extraction component within the hybrid approach.
</div>


