# Medical Data Visualizer

This project processes and visualizes patient health data to identify trends and relationships between various medical indicators and cardiovascular disease. It includes a categorical plot comparing health metrics across active and sedentary groups and a heatmap highlighting correlations between variables.

## Goals
- Analyze patient health data to identify factors correlated with cardiovascular disease.
- Provide visualizations for easy interpretation of complex medical data.

### **3. Data Description**

| **Feature**                       | **Variable Type**      | **Variable**        | **Value Type**                                          |
|------------------------------------|------------------------|---------------------|--------------------------------------------------------|
| **Age**                           | Objective Feature      | `age`               | `int` (days)                                           |
| **Height**                        | Objective Feature      | `height`            | `int` (cm)                                            |
| **Weight**                        | Objective Feature      | `weight`            | `float` (kg)                                          |
| **Gender**                        | Objective Feature      | `gender`            | Categorical code                                       |
| **Systolic Blood Pressure**       | Examination Feature    | `ap_hi`             | `int`                                                 |
| **Diastolic Blood Pressure**      | Examination Feature    | `ap_lo`             | `int`                                                 |
| **Cholesterol**                   | Examination Feature    | `cholesterol`       | `1`: normal, `2`: above normal, `3`: well above normal |
| **Glucose**                       | Examination Feature    | `gluc`              | `1`: normal, `2`: above normal, `3`: well above normal |
| **Smoking**                       | Subjective Feature     | `smoke`             | Binary (`0`: no, `1`: yes)                            |
| **Alcohol Intake**                | Subjective Feature     | `alco`              | Binary (`0`: no, `1`: yes)                            |
| **Physical Activity**             | Subjective Feature     | `active`            | Binary (`0`: no, `1`: yes)                            |
| **Presence of Cardiovascular Disease** | Target Variable | `cardio`            | Binary (`0`: no, `1`: yes)                            |

#### **Key Insights**
- The dataset includes objective measurements such as **age**, **height**, and **weight**, as well as examination results like **blood pressure** and **cholesterol levels**.
- Subjective health indicators, such as **smoking**, **alcohol consumption**, and **physical activity**, provide additional context for lifestyle choices.
- The **target variable**, `cardio`, indicates whether a patient has been diagnosed with cardiovascular disease.
