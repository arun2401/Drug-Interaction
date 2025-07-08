# Medication Interaction Checker

This is a Python-based tool that analyzes a patient's medication list and identifies potentially dangerous drug-drug interactions. The system uses a public dataset from Kaggle and is designed with modularity, clarity, and real-world use in mind.

## Features

- Detects drug-drug interactions from a verified interaction dataset
- Classifies interactions by severity level: high, moderate, low, or unknown
- Accepts custom medication input from the user
- Sorts alerts based on severity to prioritize risk
- Modular code structure:
  - `DrugDatabase`: Loads and standardizes drug data
  - `InteractionChecker`: Checks all pairwise drug combinations
  - `AlertSystem`: Sorts and displays interaction warnings

## Dataset

**Source**: [Kaggle - Drug-Drug Interactions](https://www.kaggle.com/datasets/mghobashy/drug-drug-interactions)

This dataset contains known drug interaction pairs, descriptions, interaction types, and severity labels. It includes thousands of drug pairs commonly prescribed in clinical settings.

**Fields used:**
- `drug1`, `drug2`: The pair of interacting drugs
- `description`: Explanation of the interaction
- `severity`: Severity classification (e.g., high, moderate, low)



