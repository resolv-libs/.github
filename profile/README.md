# Resolv: Machine Learning Development for Research

**Resolv** is a system designed to streamline machine learning and deep learning workflows for **research purposes**. The focus is on providing a comprehensive platform that facilitates model development, data processing, and infrastructure management. The system is organized into multiple components, each handling a specific part of the machine learning workflow. 

The goal is to create a **flexible, scalable and reusable system** that supports model experimentation, improves data processing through well-structured pipelines, and automates orchestration using modern tools like **Keras**, **Apache Beam**, and **Apache Airflow**. Resolv is built to serve as a flexible and modular system aimed at supporting research in machine learning and deep learning: the organization of the system allows for clear separation of tasks by making it easier to experiment with new ides and techniques.

## System Components

### 1. **ML/DL Models and Training Utilities**
This component contains a collection of machine learning and deep learning model implementations, along with tools for training, evaluating, and deploying models. It is written in **Keras** and offers reusable components for building a wide range of models.

- **Scope:** Machine learning and deep learning model implementations.
- **Key Tools:** Keras, TensorFlow.
- **Functionality:** Model architectures, training utilities, and tools for preprocessing and evaluation.

### 2. **Data Pipelines**
This component is responsible for managing data pipelines, including the generation and preprocessing of datasets. Using **Apache Beam**, these pipelines are designed to work at scale, offering flexibility for handling large datasets both locally and in distributed environments.

- **Scope:** Scalable data pipelines for dataset generation.
- **Key Tools:** Apache Beam.
- **Functionality:** ETL processes, synthetic data generation, and data transformation pipelines.

### 3. **Data Sources**
This component defines all available data sources used within the Resolv system. It provides schemas, configurations, and utilities for connecting to various datasets, ensuring consistency and accessibility across all pipelines and model training tasks.

- **Scope:** Centralized management of data sources.
- **Functionality:** Data source definitions, connectors for databases, APIs, and cloud storage.

### 4. **Infrastructure**
This component handles the orchestration of data pipelines and machine learning workflows using **Apache Airflow**. It manages the scheduling and execution of tasks, ensuring efficient coordination of the entire workflow.

- **Scope:** Orchestration of pipelines and workflow management.
- **Key Tools:** Apache Airflow.
- **Functionality:** DAGs for task scheduling, monitoring, and pipeline execution management.

## Open to Collaboration
If you're interested in contributing to the development of Resolv, feel free to reach out to discuss potential areas for collaboration.
