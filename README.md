# Student Lifestyle Analysis

## Project Overview

The **Student Lifestyle Analysis** project focuses on examining the impact of students' lifestyle habits on stress levels, academic performance (GPA), sleep hours, and physical activity. Using data collected from students, I conducted data exploration, correlation analysis, and built predictive models to better understand the factors influencing students' lives.

The primary goal of the project was to create a predictive model for students' stress levels. Ultimately, the project achieved **94% accuracy** in predicting stress, demonstrating the robustness of the applied analytical methods and models.

---

## Project Results

### 1. Predictive Model

- Best model: **k-Nearest Neighbors**
- Achieved accuracy: **94%**
- Key factors influencing stress:
  - Number of sleep hours
  - Level of physical activity
  - GPA performance

---

### 2. Correlation Between Features

The heatmap below illustrates the correlations between variables such as stress, physical activity, sleep hours, and GPA. Interestingly, **lower stress levels are strongly correlated with worse academic performance**, highlighting the importance of maintaining a balanced lifestyle.

![correlation](https://github.com/user-attachments/assets/0cf1ee3c-b64b-44b4-88c5-f2b3ae67859a)

---

### 3. Individual Student Analysis

The following visualizations showcase one of the most surprising students in the dataset:
1. This student spends **the least amount of time studying**, yet achieves one of the highest GPAs among all participants.
2. Despite having **low stress levels**, the student maintains outstanding academic performance.

#### Example:

![best_student1](https://github.com/user-attachments/assets/7b69760d-25d1-4523-871f-5d63c654b140)
![best_student2](https://github.com/user-attachments/assets/1a2c70e5-ab38-4f0a-a2bd-17beb5394597)

---

### 4. Confusion Matrices – Model Evaluation

The confusion matrices below highlight the performance of the models on test datasets. Both the KNN and Logistic Regression models demonstrated strong predictive capabilities.

#### KNN (k-Nearest Neighbors) & Logistic Regression:

![confusion](https://github.com/user-attachments/assets/3fd8d7ab-753e-4299-8071-edcb0eaf4b44)

---

## Technologies Used

- **Python**: NumPy, pandas, scikit-learn, Matplotlib, Seaborn
- **Data Visualization**: Pairplots, Heatmaps, confusion matrices
- **Algorithms**: Logistic Regression, k-Nearest Neighbors
- **Hyperparameter Tuning**: GridSearchCV

---













