# TikTok engagement analysis

This project aims to analyze and compare the net engagement of TikTok videos that are moderated versus unmoderated. The goal is to identify the relationship between user engagement and moderatable content. Based on engagement patterns, the project will also develop predictive models to determine whether content is likely to be moderated.

## Table of contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Data](#data)
- [Analysis and Results](#analysis-and-results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project overview

The main objectives of this project are:
- To explore and compare the engagement metrics of TikTok videos that are moderated versus those that are unmoderated.
- To identify patterns in user engagement that correlate with content moderation.
- To build a predictive model that can assess whether a TikTok video will be moderated based on its engagement metrics.

## Installation

To get started, clone the repository and install the required dependencies.

```bash
git clone https://github.com/alejandra-sofia-dbb/tiktok-engagement-analysis.git
cd tiktok-engagement-analysis
pip install -r requirements.txt

## Project structure

tiktok-engagement-analysis/
│
├── data/                   # Raw and processed data
│   ├── raw/                # Raw data files
│   └── processed/          # Processed data files used for modeling
│
├── notebooks/              # Jupyter notebooks for EDA and modeling
│   ├── unsupervised_learning_eda.ipynb  # EDA and feature exploration notebook
│   └── other_notebooks.ipynb            # Additional analysis notebooks
│
├── scripts/                # Python scripts for processing and modeling
│   ├── data_processing.py  # Scripts for data cleaning and preprocessing
│   └── modeling.py         # Scripts for training and evaluating models
│
├── results/                # Output files and figures
│   ├── figures/            # Plots and figures generated during analysis
│   └── model_outputs/      # Model outputs and evaluation results
│
├── requirements.txt        # Python dependencies
├── README.md               # Project README
└── .gitignore              # Files and directories to ignore in Git


## Usage

To explore the data, open the main EDA notebook:
jupyter notebook notebooks/unsupervised_learning_eda.ipynb

This notebook contains steps for data cleaning, visualization, and feature analysis, including calculations of engagement metrics.

## Running the scripts

Scripts for data processing and modeling can be executed from the command line:
python scripts/data_processing.py
python scripts/modeling.py

## Data

Source: The dataset was sourced from Kaggle.
Description: The dataset includes metrics such as video views, likes, shares, comments, and the moderation status of videos.

## Analysis and results

The analysis compares engagement metrics between moderated and unmoderated videos, revealing patterns that suggest why some content gets moderated.
Predictive models were developed to determine the likelihood of content being moderated based on engagement patterns.
Key findings and model performance metrics are documented in the notebooks/unsupervised_learning_eda.ipynb notebook and the results/ folder.




