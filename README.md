# Team6_DataDynamos_PythonHackathon_MAY-2026

## Description-
This dataset focuses on patients with Type 1 Diabetes Mellitus (T1DM) and contains continuous health monitoring data collected from wearable-device sources. The dataset includes glucose readings, insulin delivery information (basal and bolus rates), heart rate, physical activity (step counts), sleep patterns, demographic information, and other physiological markers.

## Problem statement-
To analyze and understand how lifestyle behaviors, physiological responses, and insulin management influence glucose control and overall diabetes outcomes.

## Methods and analysis-
### Tools and libraries used:
```python
pandas        # data manipulation
numpy         # numerical operations
matplotlib    # data visualization
scipy.stats   # pearson correlation, t-tests
scikit-learn  # predictive modelling
openpyxl      # excel file handling
```
## Key Findings-

### 1. Glucose Distribution & Daily Trends
- Nearly all patients experienced multiple stages of blood glucose fluctuation throughout the monitoring period, with 24 out of 25 patients recording low glucose levels and all 25 patients experiencing normal, high, and very high glucose ranges, indicating strong intra-patient glycemic variability across the dataset.

### 2. Correlation Analysis
- Correlation analysis showed that glucose has only a weak relationship with physical activity and heart rate, with correlations of **0.05** and **0.10**, respectively.
- In contrast, strong positive correlations were observed between:
  - **Steps and calories burned (0.80)**
  - **Heart rate and calories burned (0.57)**

These findings suggest that while physical activity strongly influences calorie expenditure, glucose variability is affected by a broader combination of physiological and behavioral factors.

### 3. Age, Sleep, and Glucose Patterns
- The **21–40 age group** recorded the highest average glucose level at approximately **161.2 mg/dL**, while maintaining moderate sleep quality.
- The **61–80 age group** showed the lowest sleep percentage at **42.5%**, alongside consistently elevated glucose levels.
- These findings suggest a potential relationship between aging, declining sleep quality, and glucose management challenges in T1DM patients.

### 4. High-Risk Patient Events
- A total of **1,395 high-risk events** were identified across **21 patients**.
- One patient, **HUPA0027P**, alone accounted for **920 events**, highlighting a significantly elevated risk profile and the need for targeted clinical intervention.

### 5. Demographic Risk Analysis
- Risk analysis across demographic groups showed that patients aged **51–65** experienced elevated risk levels across multiple categories.
- Among these groups, **Hispanic females aged 51–65** demonstrated the highest relative risk score of **3.38**.
- Conversely, **Hispanic males aged 36–50** showed the lowest relative risk score of **2.15**, indicating variability in diabetes risk patterns across demographic populations.

### 6. Basal Rate Diagnostics
- Basal insulin requirements peaked in the **40–50 age group**, averaging approximately **0.08 units/hour**.
- After age 50, basal insulin requirements showed a gradual decline, reaching nearly **0.03 units/hour** in the **70–80 age group**.
- These age-related physiological differences may play an important role in improving personalized diabetes management and predictive modeling.

## Team Members:
Pooja Belure, Jyothi Gujjari, Vyshnavi Andhavarapu, Archana Saurav, Suparna Singh

