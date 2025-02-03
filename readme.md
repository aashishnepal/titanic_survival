```markdown
# Titanic Survival Prediction

This project implements and compares three machine learning models to predict Titanic passenger survival.

## Requirements
- Python 3.8+
- Dependencies:
  ```bash
  pip install pandas numpy scikit-learn tensorflow
  ```

## Dataset
- Source: [Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- Automatically downloaded during script execution

## How to Run
1. **Install dependencies**:
   ```bash
   pip install pandas numpy scikit-learn tensorflow
   ```

2. **Save the code**:
   - Create a Python file `titanic_survival_prediction.py` and paste the code into it

3. **Execute**:
   ```bash
   python titanic_survival_prediction.py
   ```

## Output
- Classification reports for:
  - Logistic Regression
  - Random Forest
  - Neural Network
- Performance comparison table

## Code Structure
1. **Data Preprocessing**:
   - Handles missing values
   - Feature engineering
   - Train/test split (80/20)

2. **Models**:
   - Logistic Regression (scikit-learn)
   - Random Forest (scikit-learn)
   - Neural Network (TensorFlow)

3. **Evaluation**:
   - Metrics: Accuracy, Precision, Recall, F1-Score
```
