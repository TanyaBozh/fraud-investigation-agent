# Fraud Investigation Agent

A machine learning project focused on detecting fraudulent financial transactions and developing an AI agent to support fraud investigation.

## About

The project uses the **PaySim synthetic financial transaction dataset** to explore fraud detection methods and build a foundation for a fraud investigation agent.

The long-term goal is to develop a system that can identify suspicious transactions, assess model predictions, and provide interpretable explanations to support fraud analysis.

## Current Progress

**Stage 1: Dataset Exploration**

- Loaded and inspected the PaySim dataset.
- Analyzed the target variable and class imbalance.
- Checked missing values and duplicate records.
- Explored transaction types, amounts, and account balance changes.
- Investigated differences between fraudulent and legitimate transactions.

## Dataset

PaySim is a synthetic dataset simulating mobile money transactions. The dataset is stored locally and is not included in this repository.

The target variable is `isFraud`, which indicates whether a transaction is fraudulent.

## Tech Stack

- Python
- pandas
- NumPy
- Jupyter Notebook
- Git and GitHub

## Repository Structure

- `notebooks/` — exploratory data analysis and experiments
- `src/` — project source code
- `tests/` — tests
- `evaluation/` — model evaluation
- `data/` — local datasets, excluded from version control

## Roadmap

1. Complete dataset exploration.
2. Prepare features and define a reliable train/test split.
3. Train baseline fraud detection models.
4. Evaluate model performance using metrics suitable for imbalanced classification.
5. Investigate model predictions and develop fraud investigation logic.
6. Build an AI agent that can explain suspicious transactions and support further analysis.

## Notes

This is a learning and portfolio project. Since PaySim is synthetic, model performance and discovered patterns may not fully reflect real-world fraud detection scenarios.
