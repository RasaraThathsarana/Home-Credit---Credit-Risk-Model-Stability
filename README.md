# Home Credit - Credit Risk Model Stability

## Overview
The goal of this competition is to predict which clients are more likely to default on their loans. The challenge focuses on developing a model that is not only accurate but also stable over time, addressing the real-world need for consistent performance in credit risk assessment.

## Goal
Develop a machine learning model that predicts the likelihood of clients defaulting on their loans, with a focus on maintaining stability in predictive performance over time.

## Timeline
- **Start**: February 5, 2024
- **Entry Deadline**: May 20, 2024
- **Team Merger Deadline**: May 20, 2024
- **Final Submission Deadline**: May 27, 2024

## Description
Consumer finance providers need accurate methods to assess loan risk, especially for clients with little or no credit history. Traditional scorecards require regular updates to maintain performance, but these updates are time-consuming. A model that remains stable over time can significantly improve the reliability of credit risk assessments, ensuring loans are granted to suitable clients while reducing risks for providers.

The challenge involves predicting loan default risk using a stability metric that combines AUC and performance consistency over time. Your participation could lead to a more reliable way to assess loan risk, benefiting both providers and clients, particularly those with limited credit histories.

## Evaluation
Submissions are evaluated using a gini stability metric, which assesses both the predictive power and stability of the model over time. The final stability metric is calculated as:


Where `gini` is calculated weekly, `a` is the slope of a linear regression through the weekly gini scores, and `std(residuals)` measures variability in predictions.

## Submission File Format
Submissions must be in CSV format with the following structure:

