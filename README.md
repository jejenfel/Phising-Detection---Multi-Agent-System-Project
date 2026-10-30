# Multi-Agent AI-Based Phishing Detection System

## Overview

This project presents an AI-based multi-agent system designed to detect and analyze phishing URLs. The system combines machine learning-based classification with multiple specialized agents to support phishing detection and provide additional reasoning and information retrieval.

The project was developed as part of an academic group project.

## Project Objectives

- Detect phishing URLs using machine learning techniques.
- Process and analyze URL-based features.
- Integrate multiple specialized agents for classification, reasoning, and information retrieval.
- Improve the analysis process through a multi-agent approach.

## System Architecture

The system consists of multiple agents with distinct responsibilities:

1. **Classification Agent** – Analyzes URL features and predicts whether a URL is phishing or legitimate.
2. **Reasoning Agent** – Provides additional reasoning based on classification results.
3. **Search Agent** – Retrieves supporting information to assist the analysis process.

See `docs/system_architecture.png` for the system architecture.

## Dataset

The project used a dataset containing **176,262 URLs** for phishing detection experiments.

Dataset preprocessing included:
- Data cleaning and normalization
- Feature engineering
- Handling class imbalance using SMOTE

*Note: Dataset availability and source details should be documented here.*

## Technologies & Methods

- Python
- Machine Learning
- Multi-Agent System
- Feature Engineering
- Data Preprocessing
- SMOTE

## Results

The model achieved the following reported evaluation results:

- Accuracy: 99.99%
- Precision: 100%
- Recall: 100%
- F1-Score: 100%

These results reflect the evaluation performed during the academic project. Refer to the evaluation files for further details.

## Repository Structure

```text
├── dataset/       # Dataset information
└── README.md
```

## Disclaimer

This project was developed for academic and educational purposes. It is intended to support phishing detection research and awareness.
