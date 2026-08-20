# Multimodal Machine Learning for YouTube Engagement

## Overview

This project investigates how visual and textual cues in nonprofit
organization (NPO) YouTube thumbnails influence audience engagement.

The project combines computer vision, natural language processing,
feature engineering, and statistical modeling to analyze a large-scale
YouTube dataset.

## Research Question

How do visual and textual characteristics of nonprofit YouTube
thumbnails influence video engagement?

## Data

The dataset contains thousands of nonprofit YouTube videos and includes:

- Video engagement metrics
- Facial emotion features
- Face size and position
- Text overlay features
- Colorfulness
- Color complexity
- Brightness
- Saturation
- Image quality
- Title emotion
- Video duration
- Channel subscribers

## Methods

### Computer Vision
- Face detection
- Facial emotion recognition
- Face area and spatial position extraction
- Image color analysis
- Image quality assessment

### NLP
- Transformer-based sentiment analysis
- Title emotion intensity

### Statistical Modeling
- Generalized Linear Models
- Negative Binomial regression
- Overdispersion diagnostics
- Nonlinear effects
- Interaction effects
- Mean-centering
- Clustered standard errors

## Key Findings

- Visual characteristics can have nonlinear relationships with engagement.
- Color complexity shows evidence of a nonlinear relationship with engagement.
- Facial emotional cues interact with visual characteristics of thumbnails.
- Textual emotional intensity can influence audience engagement.

## Technologies

Python | SQL | Pandas | NumPy | OpenCV | Transformers |
Statsmodels | Scikit-learn | Power BI | Tableau

## Project Structure

```text
notebooks/     Analysis notebooks
src/           Data processing and modeling code
results/       Model outputs and figures
docs/          Methodology documentation
