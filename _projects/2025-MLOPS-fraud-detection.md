---
title: "MLOps for deploying of a fraud detection model"
collection: projects
permalink: /projects/2025-MLOPS-fraud-detection/
---

This project was developed as part of the MLOps Zoomcamp certification and delivers a microservice for mobile money operators across Africa to identify and block fraudulent transactions in real time. [certificate](https://nd-serge.github.io/files/mlops-zoomcamp.pdf)

- [Github - MLOps Fraud detection](https://github.com/nd-serge/mobile-money-fraud-detection)

### Context
---
<div style="text-align: justify;">

The project addresses a critical challenge in many parts of Africa where mobile money services serve as a primary tool for financial inclusion, yet users are vulnerable to sophisticated fraud tactics. The aim is to develop a fraud detection microservice that mobile money operators can use to identify and block fraudulent transactions in real time. The system is designed to improve financial security for users with limited cybersecurity knowledge, leveraging public synthetic transaction data simulated by the PaySim dataset from Kaggle.
</div>

### Methodology
---
<div style="text-align: justify;">
To build the fraud detection pipeline, the repository orchestrates an end-to-end workflow using modern tools like Prefect for task orchestration and MLflow for experiment tracking and model registry. The process begins by downloading and preprocessing the PaySim dataset, including filtering and cleaning steps, followed by training machine learning models with hyperparameter tuning. The best model—selected based on average F1 score—is registered using MLflow. A microservice, implemented with FastAPI, exposes a /predict endpoint to make real-time predictions using the trained model. The entire workflow is automated via a Makefile and containerized deployment.
</div>

### Result
--- 
<div style="text-align: justify;">

The repository is structured to automate model training and deployment, including experiment tracking and model selection. While specific performance metrics (e.g., F1 score, accuracy) are configurable by the workflow and model choice, the project’s implementation emphasizes reproducibility and traceability through Prefect and MLflow, supporting continuous improvement and deployment readiness of the fraud detection service.
</div>


