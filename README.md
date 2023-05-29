# MLflow
Step by Step Integration with MLflow


## OverView
MLflow is an open-source platform designed to manage the end-to-end machine learning lifecycle. It provides a set of tools and APIs that enable data scientists and machine learning practitioners to track, reproduce, and deploy machine learning models.

### Components (v.2.3)
MLflow supports four major components 
- Tracking: It allows to track model experiments, logs parameters,code version (git commit hash) metrics, start & end time and artifacts during development process. It also provides UI to visualize compare and search runs

- Projects: MLflow Projects provide a format for packaging machine learning code in a reusable and reproducible manner. A project is essentially a directory containing code, dependencies, and configuration files. It allows you to specify the entry point to your training or evaluation code and package it for easy execution on different platforms.

- Models: The models component helps you manage and deploy machine learning models in different formats (e.g., Python functions, serialized models). It provides a standardized format called the "MLflow Model" that allows you to package models with associated metadata, such as input/output schemas, dependencies, and model versions. MLflow also supports model serving for deploying models in real-time inference or batch prediction scenarios.

- Model Registry: The registry component allows you to store, organize, and manage models in a central repository. It provides versioning, model lineage tracking, and model access control. The registry enables collaboration among team members by allowing them to discover, share, and deploy models easily.

MLflow is designed to be agnostic to the underlying machine learning framework, allowing you to use it with popular libraries such as TensorFlow, PyTorch, scikit-learn, and XGBoost