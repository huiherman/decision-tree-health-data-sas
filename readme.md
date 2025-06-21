# Decision Tree Classification Using SAS Model Studio

## 📌 Description
This project explores the performance of decision tree models applied to a health dataset using SAS Model Studio. Two tree models are created with different pruning strategies to compare classification accuracy and complexity.

## 🎯 Objective
To evaluate the impact of pruning methods on classification performance by comparing simple decision trees with different configurations using key metrics such as number of leaves, misclassification rate, and KS (Youden) statistic.

## 📁 Project Structure
- `DTree_1`: Simple Decision Tree using default pruning
- `DTree_2`: Decision Tree using reduced error pruning
- Target variable: `Status`
- Input variables: `SEX`, `HEIGHT`, `WEIGHT`, `DIASTOLIC`, `SYSTOLIC`, `SMOKING`, `CHOLESTEROL`, `BP Status`

## 📊 Key Results
- **DTree_1**:
  - 13 leaves after pruning
  - Most significant variable: Systolic
  - Misclassification rate: 0.3214
  - KS (Youden): 0.2260

- **DTree_2**:
  - 8 leaves after pruning
  - Improved KS (Youden): 0.2619
  - More accurate than DTree_1

## 🎓 Learning Outcomes
- Gained hands-on experience with SAS Model Studio’s machine learning pipeline
- Learned how tree pruning impacts model accuracy and complexity
- Practiced evaluating models using misclassification and KS statistic
- Understood health data structure and variable selection for classification

## 🔗 Repository URL
[github.com/hermanhui/decision-tree-health-data-sas](https://github.com/hermanhui/decision-tree-health-data-sas)

## 🧠 Skills Applied
SAS Model Studio, health data classification, decision tree pruning, KS statistic analysis, model validation
