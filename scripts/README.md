## B5W1: Predicting Price Moves with News Sentiment

Overview

This repository contains the code and documentation for the B5W1: Predicting Price Moves with News Sentiment challenge at Nova Financial Insights. The project analyzes the Financial News and Stock Price Integration Dataset (FNSPID) to explore correlations between news sentiment and stock price movements. The goal is to derive actionable investment strategies using exploratory data analysis (EDA), technical indicators, and sentiment analysis.

## Project Structure

The repository is organized as follows:

```

├── .github/
│   └── workflows/
│       └── unittests.yml    # CI/CD pipeline for unit tests
├── .vscode/
│   └── settings.json        # IDE settings
├── notebooks/
│   ├── __init__.py
│   ├── README.md            # Notebook descriptions
|
|── scripts/
    ├── __init__.py
    ├── README.md            # Script
├── src/
│   ├── __init__.py          # Python package initialization
├── tests/
│   ├── __init__.py          # Unit tests
├── .gitignore               # Files to ignore in version control
├── environment.yml         # Python dependencies
├── README.md                # Project documentation (this file)


```

## Setup Instructions

To set up the project locally, follow these steps:

1. Clone the Repository:

```bash
git clone git@github.com:moablex/B5W1_Financial_Analysis.git

cd B5W1_Financial_Analysis

```

2. Create a Virtual Environment (recommended):

```bash
conda create -n .venv python=3.10
conda activate .venv
```

3. Install Dependencies:

```bash
conda env create -f environment.yml

```
