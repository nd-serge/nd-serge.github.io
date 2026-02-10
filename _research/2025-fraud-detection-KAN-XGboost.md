---
title: "Fraud detection using Kolmogorov-Arnold Network (KAN)-XGboost"
collection: research
permalink: /research/2025-fraud-detection-KAN-XGboost/
paperurl: 'https://www.preprints.org/frontend/manuscript/aca2ef32d9c8f560f9d4a44368033b0f/download_pub'
citation: 'Nolack Tapsir Gislain Zeutouo, Evgeniy Yurievich Kostyuchenko, and Serge Ndoumin (2025). &quot;An Ensemble KAN-XGBoost Model for Fraud Detection.&quot;'
---

This study builds on the work of _Gislain, Zeutouo & Yurievich, Kostyuchenko. (2025). Fraud detection using Kolmogorov-Arnold Network._ and aimed to improve the performance of the initial fraud detection model for Mobile Money transactions, which is based on the KAN algorithm [paper](https://www.researchgate.net/publication/389639889_Fraud_detection_using_Kolmogorov-Arnold_Network). More specifically, it seeks to optimize data preprocessing to enhance model convergence and to reduce false negatives and false positives by combining the KAN model with the XGBoost algorithm.


- [Kaggle - Fraud detection using KAN-XGboost](https://www.kaggle.com/code/sergendoumin/fraud-detection-using-kan-xgboost)
- [Technical report - Fraud detection using KAN-XGboost](https://docs.google.com/document/d/1iK2RezLUiKKTOVnhOGGjLFXXCHx40LhQKPr7QmCnVdI/edit?usp=sharing)
- Co-authors [Nolack Tapsir Gislain Zeutouo](mailto:), [Evgeniy Yurievich Kostyuchenko](mailto:)

### Context
---
<div style="text-align: justify;">

Financial fraud represents a growing challenge for financial institutions and e-commerce platforms, requiring increasingly sophisticated detection methods. While traditional machine learning models have proven effective, they often struggle with complex fraud patterns. 
</div>

### Methodology
---
<div style="text-align: justify;">
This work proposes a novel ensemble approach, KAN-XGBoost, which combines Kolmogorov-Arnold Networks (KAN) for learning complex relationships with the robustness of Extreme Gradient Boosting (XGBoost) for high-performance classification. Experiments are conducted using the synthetic PaySim dataset. To address the severe class imbalance, the Synthetic Minority Oversampling Technique (SMOTE) is applied to the training data. The ensemble model is implemented using a soft voting strategy.
</div>

### Result
--- 
<div style="text-align: justify;">

Experimental results show that the KAN-XGBoost ensemble model significantly outperforms the individual models, achieving performance metrics of 99%. These results highlight the effectiveness of hybridizing KANs with established boosting algorithms and suggest a promising approach for enhancing the security of financial transactions.
</div>


