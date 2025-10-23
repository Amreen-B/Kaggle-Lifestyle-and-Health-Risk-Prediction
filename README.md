# 🏥 Lifestyle & Health Risk Dataset

Lifestyle and health dataset designed for building and evaluating health risk prediction models. The dataset mimics realistic human wellness data — without the use of sensitive or private medical information — and is ideal for EDA, classification modeling, and web app development.
This synthetic dataset simulates lifestyle and wellness attributes for 5,000 individuals. It is generated using heuristic, rule-based methods to imitate real-world health risk behavior patterns, making it safe for public experimentation and machine learning workflows.

---

## 🧾 Features

| Column         | Description                                      | Type                               | Example          |
|----------------|--------------------------------------------------|------------------------------------|------------------|
| `age`          | Age of the person (years)                        | Numeric                             | 35               |
| `weight`       | Body weight in kilograms                         | Numeric                             | 70               |
| `height`       | Height in centimeters                            | Numeric                             | 172              |
| `exercise`     | Exercise frequency level                         | Categorical (none, low, medium, high) | medium        |
| `sleep`        | Average hours of sleep per night                 | Numeric                             | 7                |
| `sugar_intake` | Level of sugar consumption                       | Categorical (low, medium, high)     | high             |
| `smoking`      | Smoking habit                                    | Categorical (yes, no)               | no               |
| `alcohol`      | Alcohol consumption habit                        | Categorical (yes, no)               | yes              |
| `married`      | Marital status                                   | Categorical (yes, no)               | yes              |
| `profession`   | Profession type                                  | Categorical (office_worker, teacher, doctor, etc.) | teacher |
| `bmi`          | Body Mass Index (weight / height²)               | Numeric                             | 24.5             |
| `health_risk`  | Target label: overall health risk                | Categorical (low, high)             | high             |

---

## 🧪 Example Projects You Can Build

- 📊 **EDA Notebook**: Explore relationships between lifestyle variables and health risk.
- 🧠 **ML Model**: Train RandomForest, XGBoost, or Logistic Regression to predict `health_risk`.
- 📈 **SHAP Analysis**: Identify key drivers of health risk using explainable ML.

---

## ⚙️ Technical Details

- **Rows**: 5,000 (can be expanded)
- **Columns**: 12
- **Target Variable**: `health_risk`
- **Data Types**: Mixed (Numerical + Categorical)
- **Format**: CSV
