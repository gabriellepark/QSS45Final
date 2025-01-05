# QSS 45 Final: It’s Shotime: Social Media User Identity and Engagement with Shohei Ohtani Instagram Content

**Fall 2024**
**QSS 45: AI and Machine Learning for Social Science**

## Project Overview
This repository is for a final project a Quantitative Social Science course at Dartmouth College, taught by Professor Herbert Chang. This project identified differences in social media content engagement and virality factors among Asian and Asian-American sub-group users, focusing on Instagram posts on Shohei Ohtani, a Japanese baseball player for the Los Angeles Dodgers. Research methods include LDA topic modeling, CatBoost regressor models, and OpenAI’s API to preprocess social media data, translate texts, and categorize username etymology.


## Data

**1. Raw Instagram Data on Shohei Ohtani**

- **File:** `shohei-ig.csv`
- **Source:** Meta Content Library and API
- (not included due to file size)

**1. Cleaned Instagram Data on Shohei Ohtani**

- **File:** `shohei-ig-cleaned.csv.zip`
- **Source:** Meta Content Library and API


## Code
- **File:** 'data_processing.ipynb': data cleaning and processing; joining batching results to main data frame

- **File:** 'GPT-Batching-Username.ipynb': GPT batching for username likely etymology

- **File:** 'GPT-Batching-Translation.ipynb': GPT batching for text translation to English

- **File:** 'LDAModeling.ipynb': LDA modeling, VADER sentiment analysis, and BERTopic

- **File:** 'data_analysis.ipynb': Cat Boost regressor model


## Paper
Final project write-up:

- **File:** `QSS_45_Final_Project Park.pdf`



