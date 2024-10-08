# TikTok engagement analysis

This project aims to analyse and compare the net engagement of TikTok videos that are moderated versus unmoderated, using supervised learning techniques to build classification models. The primary goal is to identify patterns between engagement scores and content moderation, to predict whether a piece of content is likely to be moderated based on its engagement metrics. Moderation based on engagement scores could contribute to more proactive and scalable content moderation strategies, making it easier for content moderators to prioritise the content they look at, ultimately making platforms safer for users.

Though usually the industry prioritises other metrics such as transcripts and language analysis for such purposes, viewing the problem from this angle could potentially uncover interesting and valuable data about how people behave when faced with content that should be moderated. This could help enhance moderation workflows and improve content safety on platforms like TikTok.

The dataset consists of 19,382 rows and 12 columns, where each row represents a user-reported video. The data is sourced from Kaggle, and includes features such as claim status (whether the video contains a claim or an opinion), video view count, like count, share count, comment count, and ban status (whether the author of the video was banned or not). The dataset is well-suited for this task as it provides a range of engagement metrics that are hypothesized to correlate with moderation.

The dataset contains a mixture of numerical and categorical features:

Numerical features: video view count, like count, share count, download count, and comment count.
Categorical features: claim status, verified status, author ban status.
Data size: approximately 1.8MB in CSV format.

The full dataset description and download link are available on Kaggle (https://www.kaggle.com/datasets/raminhuseyn/dataset-from-tiktok).

## Table of contents
- [Project Overview](#project-overview)
- [Installation](#installation)
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


## Analysis and results

The analysis compares engagement scores between moderated and unmoderated videos, revealing patterns that suggest why some content gets moderated.
Predictive models were developed to determine the likelihood of content being moderated based on engagement patterns.
Key findings and model performance metrics are documented in the notebooks/unsupervised_learning_eda.ipynb notebook and the results/ folder.

For full discussion and background, refer to the notebooks.




