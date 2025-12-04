# Healthcare Synthetic Dataset

## Raw Data:
synthentic_health_data.csv
source: kaggle.com




| Column                | Type      | Description                                                     |
| --------------------- | --------- | --------------------------------------------------------------- |
| `Age`                 | float     | Age in years.                                           |
| `BMI`                 | float     | Body Mass Index.                                                |
| `Exercise_Frequency`  | int       | Exercise sessions per week.                         |
| `Diet_Quality`        | float     | Diet health score (approx. 20–100).                             |
| `Sleep_Hours`         | float     | Average nightly sleep hours.                                    |
| `Smoking_Status`      | int (0/1) | 0 = non-smoker, 1 = smoker.                                     |
| `Alcohol_Consumption` | float     | Average weekly alcohol consumption.                     |
| **`Health_Score`**    | float     | The target variable: an overall composite health score (0–100). |


## Preproccessing
* Numeric Type Enforcement for all continuous variables
* Outlier Removal
* Target Definition
