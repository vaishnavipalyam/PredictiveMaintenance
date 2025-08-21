# Predictive Maintenance for Windmills

![windmills](https://tse1.mm.bing.net/th/id/OIP.gL4nCJA7hD04IBVPlx4ipgHaEo?pid=Api&P=0&h=180)

## Project Overview

This project implements an end-to-end predictive maintenance system for windmills using deep learning. The goal is to predict potential failures before they occur, helping reduce downtime and improve operational efficiency.

The dataset consists of 20,000 training records and 5,000 test records, each containing 40 encoded sensor predictors. The predictive models are optimized specifically for recall, ensuring that potential failures are not overlooked.

## Objectives

- Build robust neural network models to predict windmill failures.

- Optimize for recall (sensitivity) to minimize false negatives.

- Provide a reproducible pipeline for data preprocessing, training, evaluation, and deployment.

## Dataset

- Training set: 20,000 records

- Test set: 5,000 records

- Features: 40 encoded sensor readings (predictors)

- Target variable: Failure indicator (binary classification: 0 = No failure, 1 = Failure)

## Methodology

1. Business context and purpose
2. data description
3. Data ingestion
4. EDA
5. Preprocessing data for modelling with missing value treatment
6. Picking the right metric
7. modelling
8. Fine tuning the models by experimenting with parameters
9. Choosing the right model
10. Model explanation
11. Business insights and recommendations

## Results

Developed 7 neural network models with varying depth, activation functions, and optimizers

Best model achieved highest recall while maintaining a reasonable balance with precision

## Insights:

Sensor features contributed differently to recall optimization

Trade-offs between recall and precision were analyzed

## Tech Stack

Languages: Python

Libraries: TensorFlow / Keras, NumPy, Pandas, Matplotlib, Scikit-learn

Tools: Jupyter Notebook, GitHub

## Future work

1. Experiment with feature selection / dimensionality reduction

2. Explore ensemble methods (stacking neural networks with traditional ML models)

3. Deploy best model as an API for real-time monitoring

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.
