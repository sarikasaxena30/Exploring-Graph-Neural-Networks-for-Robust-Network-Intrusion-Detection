**GNN-IDS: Graph Neural Network-Based Intrusion Detection System for IoT Networks**
This repository contains the implementation of GNN-IDS, a novel Intrusion Detection System leveraging Graph Neural Networks (GNNs) to enhance IoT network security. The project focuses on detecting network threats like DoS, DDoS, and spoofing while reducing false alarms by analyzing network traffic as graph-structured data.

**Key Features**

Graph Neural Networks: Captures complex relationships between devices in IoT networks.
Real-time Threat Detection: Identifies malicious activities with high accuracy.
Robust Performance: Achieves state-of-the-art detection accuracy of 99.95% on the CIC-IOT-2023 dataset.
IoT-Specific Analysis: Handles static and dynamic network features to evaluate various attack types.
**Dataset**

The CIC-IOT-2023 dataset is used for evaluation. It provides real-world IoT network traffic, categorized into benign and anomaly scenarios.

**Methodology**

**Data Preprocessing:**
Label encoding, feature scaling, and normalization.
**Graph Construction:**
Representing network devices as nodes and their interactions as edges using NetworkX and DGLGraph.
**Model Architecture:**
GraphSAGE layers integrated with a Multi-Layer Perceptron for prediction.
Training and Evaluation: Robust evaluation using precision, recall, F1-score, and accuracy.
**Performance Metrics**

**Accuracy:** 99.95%
**F1-Score:** High across most IoT-specific attack types.
Demonstrates adaptability to complex attack patterns and reduced false alarms.
**Results**

Outperforms traditional ML and DL approaches.
Provides detailed insights into IoT-specific attack detection.
