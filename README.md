# TruthSeeker-News-Analysis
## Overview

This repository contains coursework analyses of the TruthSeeker2023 dataset completed for Advanced Data Analytics at the University at Albany. Published by the Canadian Institute for Cybersecurity at the University of New Brunswick, the dataset contains tweets associated with real and fake news statements sourced from PolitiFact.

The notebooks analyze tweet text, linguistic features such as word counts and punctuation, and user metadata such as follower counts, engagement activity, and credibility scores. They use `BinaryNumTarget`, where 1 represents a true source statement and 0 represents a false source statement.

The analyses include Naive Bayes and neural network classification, K-means clustering of false-labeled tweets, and feature engineering using TF-IDF, categorical encoding, standardization, and log transformations. Together, they explore the predictive value of different feature sets, linguistic patterns within false-labeled content, and the effects of preprocessing on feature distributions.

**Dataset source:** [TruthSeeker2023 — University of New Brunswick](https://www.unb.ca/cic/datasets/truthseeker-2023.html)
