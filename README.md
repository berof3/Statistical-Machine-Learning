# Statistical Machine Learning: Bike-Sharing Demand Prediction

## Project Overview
This repository contains a comprehensive machine learning project developed for the **Statistical Machine Learning (1RT700)** course at **Uppsala University**. 

The goal of this project is to solve a binary classification problem for the District Department of Transportation in Washington D.C. (Capital Bikeshare). We aim to predict whether an increase in the number of available bicycles is required at a specific hour based on temporal and meteorological data.

### The Objective:
Predict `increase_stock`:
*   `low_bike_demand`: No increase needed.
*   `high_bike_demand`: Stock increase required.

---

## Dataset & Features
The model is trained on a dataset of 1,600 observations with features including:
*   **Temporal**: Hour of day, day of week, month, holiday/weekday status.
*   **Meteorological**: Temperature, Dew point, Humidity, Precipitation, Snowfall/depth, Windspeed, Visibility, and Cloud cover.

---

## Machine Learning Methodology
We explored and compared multiple families of classification algorithms to determine the most robust model for "production" use:

1.  **Logistic Regression**: Establishing a baseline for linear separability.
2.  **Discriminant Analysis**: Implementing and comparing **LDA** and **QDA**.
3.  **K-Nearest Neighbors (KNN)**: Non-parametric approach with hyperparameter tuning.
4.  **Tree-Based Methods**: Utilizing **Classification Trees**, **Bagging**, and **Random Forests**.
5.  **Boosting**: Implementing ensemble methods to improve predictive accuracy.

### Optimization & Evaluation
*   **Hyperparameter Tuning**: Utilized Systematic Grid Search and Random Search to optimize model performance.
*   **Validation**: Employed **k-fold Cross-Validation** to ensure model generalizability and prevent overfitting.
*   **Performance Metrics**: Evaluated models based on **Accuracy, F1-score, Precision, and Recall** to handle potential class imbalances.

---

## Repository Structure
*   **/Colab notebooks**: Contains the Jupyter/Colab notebooks used for Exploratory Data Analysis (EDA), model implementation, and tuning.
*   **/Docs**: Includes the final technical report (NeurIPS format) detailing the mathematical foundation, experimental setup, and conclusions.

---

## Tech Stack
*   **Language**: Python
*   **Libraries**: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
*   **Formatting**: LaTeX (for technical reporting)
 
