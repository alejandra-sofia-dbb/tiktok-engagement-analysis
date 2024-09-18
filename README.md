# TikTok engagement analysis

This project aims to analyse and compare the net engagement of TikTok videos that are moderated versus unmoderated. The goal is to identify the relationship between user engagement and moderatable content. Based on engagement patterns, the project will also develop predictive models to determine whether content is likely to be moderated. 

The concept of moderating based on engagement patterns provides an interesting route to safety strategies. 

The dataset features 19,382 rows and 12 columns. Each row represents one user's report, offering insights into the reported content.

## Table of contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Analysis and Results](#analysis-and-results)

## Project overview

The main objectives of this project are:
- To explore and compare the engagement metrics of TikTok videos that are moderated versus those that are unmoderated.
- To identify patterns in user engagement that correlate with content moderation.
- To build a predictive model that can assess whether a TikTok video will be moderated based on its engagement metrics.

## Installation

To start, clone the repository and install the required dependencies.

```bash
git clone https://github.com/alejandra-sofia-dbb/tiktok-engagement-analysis.git
cd tiktok-engagement-analysis
pip install -r requirements.txt
```

## Usage

To explore the data, open the main EDA notebook: ```bash
jupyter notebook notebooks/unsupervised_learning_eda.ipynb```

This notebook contains steps for data cleaning, visualization, and feature analysis, including calculations of engagement metrics.

## Running the scripts

Scripts for data processing and modeling can be executed from the command line:
```bashpython scripts/data_processing.py
python scripts/modeling.py
```
## Data

Source: The dataset was sourced from Kaggle.
Description: The dataset includes metrics such as video views, likes, shares, comments, downloads and the moderation status of videos.

## Analysis and results

The analysis compares engagement scores between moderated and unmoderated videos, revealing patterns that suggest why some content gets moderated.
Predictive models were developed to determine the likelihood of content being moderated based on engagement patterns.
Key findings and model performance metrics are documented in the notebooks/unsupervised_learning_eda.ipynb notebook and the results/ folder.




