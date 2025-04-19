# AI Ghibli Trend Analysis

This repository contains an analysis of AI-generated Studio Ghibli-inspired images and their engagement metrics across different social media platforms. The dataset includes 500 images with various attributes including platform distribution, engagement metrics, technical specifications, and style accuracy scores.

![Included as many movies as I could #studioghibli #ghibli](https://github.com/user-attachments/assets/a125eadf-22c9-4296-84bb-216eac25ddb0)


## Dataset Overview

The dataset contains information about 500 AI-generated images inspired by Studio Ghibli's distinctive art style. 
Each entry includes:
 Image ID and user ID
Prompt used to generate the image
Engagement metrics (likes, shares, comments)
Platform where the image was shared
Technical details (generation time, GPU usage, file size, resolution)
Style accuracy score
 Hand-editing status
 Ethical concerns flagging
Creation date
Top comment

## Key Insights

### Platform Distribution
 Images are distributed across four main platforms: Instagram, Reddit, TikTok, and Twitter
 There's a relatively balanced distribution of content across these platforms

### Engagement Metrics
 TikTok and Twitter show the highest total likes across all posts
 Reddit has more polarized engagement metrics with higher variance in comments
 Instagram shows more consistent engagement patterns

### Technical Analysis
 There's a correlation between GPU usage and generation time
 Hand-edited images generally have higher style accuracy scores
 Images with higher style accuracy tend to receive more engagement

### Content Themes
 "Ghibli-style" is the most common theme in prompts
 "Magical" and "Mysterious" themes are also frequently used
 Several distinct aesthetic patterns appear across the dataset

### Ethical Considerations
 A notable portion of images are flagged for ethical concerns
 The distribution of ethical concern flags varies by platform

## Scripts

The main analysis script includes:
 Data loading and preprocessing
 Exploratory data analysis
 Visualization of engagement metrics by platform
 Analysis of prompt themes and content patterns
 Correlation analysis between technical metrics and engagement

## Requirements

 Python 3.x
 pandas
 numpy
 matplotlib
 seaborn

## Usage

```python
# Load and explore the dataset
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Load the dataset
df = pd.read_csv("ai_ghibli_trend_dataset_v2.csv")

# Run visualizations and analysis
# (See individual code sections in the notebook)
```

## Visualizations

The repository includes visualizations for:
 Platform distribution
 Engagement metrics by platform
 Prompt theme analysis
 Technical metadata correlations
 Style accuracy analysis

## Future Work

 Sentiment analysis of top comments
 Time series analysis of engagement trends
 More detailed content analysis based on the prompts
 Performance comparison with non-Ghibli AI art
