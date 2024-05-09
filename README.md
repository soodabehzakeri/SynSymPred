# SynSymPred
# SYNSIMPRED: Synthetic Lethality Prediction

## Overview

SYNSIMPRED is a predictive tool designed to identify potential synthetic lethality in cancer treatment. This tool leverages various datasets, including RNA expression, mutation data, and copy number variations, to predict synthetic lethality using cross-validation techniques and various machine learning metrics.

## Installation

Ensure you have Python installed along with the required libraries. You can install the necessary packages using `pip`:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
## Usage

To effectively use SYNSIMPRED, complete the following steps:

1. **Clone the Repository:** Clone this repository to either a local machine or a Google Colab environment.
2. **Configure Data Paths:** Ensure that the data files (in `.csv` format) are located in the paths specified within the scripts, or update these paths according to your setup.
3. **Run the Notebook:** Execute the notebook cells in sequence to perform data analysis and synthetic lethality predictions.

## Data Description

SYNSIMPRED utilizes the following datasets:

- **RNA Expression Levels:** Measures the expression levels of RNAs in different cell lines.
- **Genetic Mutation Data:** Contains information on genetic mutations present in various cell lines.
- **Copy Number Variations:** Records variations in the number of copies of particular genes.
- **Cell Line Dependency Scores:** Reflects how essential specific genes are to the survival of cell lines.

Place your data files in an accessible directory, typically at `'/content/drive/MyDrive/depmap cells/'`.

## Features

SYNSIMPRED offers a range of features to facilitate the prediction of synthetic lethality:

- **Data Loading and Preprocessing:** Prepares and cleans the data for analysis.
- **Correlation Metrics Calculation:** Computes various correlation metrics to support model predictions.
- **Prediction Model Implementation:** Deploys models to predict potential synthetic lethality.
- **Performance Evaluation:** Assesses model accuracy using precision, recall, F-score, and other relevant metrics.

## Contributing

We encourage contributions to SYNSIMPRED. If you have suggestions for improvement or new features, please fork the repository and submit a pull request with your changes.

