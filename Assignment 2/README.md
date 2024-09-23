# Advanced ML Second Assignment

## Overview

This assignment is divided into three main sections: Exploratory Data Analysis (EDA) with Statistical Tests, SQL Queries, and Deep Learning Model Implementation. Each section focuses on a specific dataset and aims to apply various data science techniques to derive insights and build models.

## Assignment Sections

### 1. EDA and Statistical Tests

#### Dataset: Bank Marketing Dataset
- **Link**: [Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)

1. **Data Cleaning and Exploration**:
   - Explore and clean the dataset, detailing imputation techniques and categorical encoding choices.
   
2. **Feature Relations**:
   - Investigate relationships between features using visualizations from [Data to Viz](https://www.data-to-viz.com). Justify the chosen graphs.

3. **Time-Related Analysis**:
   - Analyze time-related columns and their correlation with the target variable to uncover hidden insights.

4. **Hypothesis Testing**:
   - Understand the role of hypothesis tests in EDA and model building.
   - Conduct tests on:
     - The effect of marital status on personal loan uptake.
     - The influence of previous marketing campaigns.
     - The relationship between job type and credit default.

5. **Additional Hypothesis Tests**:
   - Design two further tests to explore the dataset.

6. **T-Tests**:
   - Explain t-tests and their implications, conducting a one-sample t-test on the dataset.
   - Identify two related numerical columns for paired t-tests, explaining the rationale and results.

7. **Chi-Square Tests**:
   - Define chi-square tests and their applications, conducting two tests and interpreting the results.

### 2. SQL

#### Dataset: San Francisco Bay Area Bike Share Dataset
- **Link**: [Bike Share Dataset](https://www.kaggle.com/datasets/benhamner/sf-bay-area-bike-share)

1. **SQL Queries**:
   - Retrieve IDs of bikes rented for over 10 days.
   - Display the top 5 most frequently rented bikes with their rental counts.
   - Get start and end station names for trips longer than 1 hour.
   - Calculate total revenue per zip code for trips exceeding 30 minutes.
   - Determine the percentage of trips subscribed by customers for each season (only trips over 15 minutes).
   - Find the most popular station based on trip ratios.

### 3. Deep Learning

#### Dataset: CIFAR-10
- **Link**: [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)

1. **Model Implementation**:
   - Implement two architectures using PyTorch:
     - **GoogLeNet**: Reference the paper [here](https://arxiv.org/abs/1409.4842).
     - **ResNet**: Reference the paper [here](https://arxiv.org/abs/1512.03385).
   - Note: Training for 2-3 epochs is sufficient. Implement lighter versions if needed.

## Requirements

- Code must be well-commented to enhance readability and understanding.
- While no formal reports are required, minimal documentation should accompany the code.


