# Persian Sentiment Analysis on Food Delivery Reviews Using FaBERT

This repository contains the code and resources for the project: Persian Sentiment Analysis Using Deep Learning Concerning the Food Delivery Sector. The study employs the FaBERT model, a BERT variant optimized for Persian, to analyze customer sentiment in the Persian language, specifically using reviews from the Snappfood platform.

# Project Overview

The paper addresses challenges posed by Persian's unique linguistic features such as rich morphology, informal usage, and dialectal variations. Traditional sentiment analysis methods struggle with these complexities, especially in domain-specific contexts like food delivery reviews. This project fine-tunes FaBERT for these challenges, optimizing its performance for sentiment analysis on Persian text.

# Objectives

- Fine-tune the FaBERT model for analyzing Persian customer reviews.
- Achieve higher accuracy and F1 scores than existing models like ParsBERT and AriaBERT.
- Evaluate the model's effectiveness in recognizing Persian slang, idiomatic expressions, and cultural references.

# Dataset

The dataset used is sourced from Snappfood, an online food delivery platform in Iran. It consists of 69,480 Persian user reviews labeled as either "HAPPY" or "SAD". The dataset is structured into training, validation, and testing sets to ensure comprehensive model evaluation.

# Results

FaBERT achieved:
    88.28% Accuracy (0.48% higher than ParsBERT)
    88.26% F1 Score (Outperforming ParsBERT and AriaBERT)
The model effectively recognized cultural references, slang, and regional dialects, demonstrating its robustness in domain-specific Persian sentiment analysis.

# Citation

If you use this work, please cite:

Hirad Pazandehkar, "Persian Sentiment Analysis Using Deep Learning Concerning Food Delivery Sector," 2024.
