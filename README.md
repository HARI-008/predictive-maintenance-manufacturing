# Predictive Maintenance for Manufacturing

## Machine Learning-Based Equipment Failure Prediction

## Project Overview

Predictive Maintenance is a Machine Learning project designed to predict potential equipment failures in manufacturing industries using machine sensor data.

Unexpected machine failures can cause production delays, increased maintenance costs, and operational losses. This project uses machine learning algorithms to analyze sensor readings and identify machines that may be at risk of failure.

The objective is to support proactive maintenance and reduce unplanned equipment downtime.

## Project Objectives

- Analyze manufacturing machine sensor data.
- Identify patterns associated with equipment failures.
- Build machine failure prediction models.
- Compare multiple machine learning algorithms.
- Evaluate model performance using classification metrics.
- Develop an interactive machine failure prediction system.

## Dataset

AI4I 2020 Predictive Maintenance Dataset

Source: UCI Machine Learning Repository

Dataset Link: https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

Dataset characteristics:

- 10,000 data records.
- Air temperature.
- Process temperature.
- Rotational speed.
- Torque.
- Tool wear.
- Machine failure labels.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Scikit-learn | Machine Learning |
| Random Forest | Failure classification |
| XGBoost | Gradient boosting classification |
| Logistic Regression | Baseline classification |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab | Development environment |
| Joblib | Model serialization |

## Project Workflow

1. Data Collection: Load the AI4I 2020 dataset.
2. Data Preprocessing: Handle missing values and prepare sensor features.
3. Exploratory Data Analysis: Analyze sensor readings and failure distributions.
4. Model Development: Train Logistic Regression, Random Forest and XGBoost.
5. Model Evaluation: Compare performance using classification metrics.
6. Prediction: Estimate machine failure probability from sensor readings.
7. Visualization: Generate model comparison charts, confusion matrices and feature importance plots.

## Machine Learning Algorithms

Three classification algorithms are implemented:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

The models are compared to identify the strongest performance on the held-out test dataset.

## Evaluation Metrics

The project evaluates model performance using:

- Accuracy
- Precision
- Recall
- F1-Score
- PR-AUC
- ROC-AUC
- Confusion Matrix

Because machine failures are relatively rare, particular attention is given to precision and recall.

## Key Features

- Machine failure prediction.
- Sensor-based risk estimation.
- Multiple machine learning model comparison.
- Interactive sensor input.
- Batch prediction using CSV files.
- Feature importance visualization.
- Automated model saving.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/HARI-008/predictive-maintenance-manufacturing.git
   ```

2. Open the notebook:

   `predictive_maintenance.ipynb`

3. Open it using Google Colab.

4. Upload the dataset to:

   `/content/ai4i2020.csv`

5. Run the notebook cells.

6. Review the model evaluation results and machine failure predictions.

## Repository Structure

```text
predictive-maintenance-manufacturing/
│
├── predictive_maintenance.ipynb
├── README.md
└── requirements.txt
```

## Future Enhancements

- Integrate real-time IoT sensor data.
- Implement LSTM for sequential sensor analysis.
- Develop Remaining Useful Life prediction.
- Build a real-time industrial monitoring dashboard.
- Integrate automated maintenance alerts.

## Limitations

The AI4I 2020 dataset is simulated and intended for research and educational purposes. The trained model requires validation using representative real-world industrial data before practical deployment.

The current classification system predicts a machine failure label and does not estimate the exact time until failure.

## Author

Harish Kumudan

B.Sc. Data Science

GitHub: https://github.com/HARI-008

