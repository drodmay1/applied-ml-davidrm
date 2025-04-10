# Lab 5: Ensemble Machine Learning – Wine Quality Prediction

This project focuses on using ensemble machine learning models to predict the quality of red wine based on chemical properties. We used the Wine Quality dataset from UCI, which includes 11 physicochemical features and a quality score rated by wine tasters.

## GitHub Repository
https://github.com/drodmay1/applied-ml-davidrm/tree/main/lab05

## Objective
Simplify the wine quality ratings into three categories:  
- Low (scores 3–4)  
- Medium (5–6)  
- High (7–8)

## Notebook Structure
The notebook `ensemble-davidrm.ipynb` includes the following sections:

- `# Lab 5: Ensemble Machine Learning – Wine Dataset`
- `## Import Libraries`
- `## Section 1: Load and Inspect the Data`
- `## Section 2. Prepare the Data`
- `## Section 3: Feature Selection and Justification`
- `## Section 4: Split the Data into Train and Test Sets`
- `## Section 5: Evaluate Model Performance`
- `## Section 6: Compare Results`
- `## Section 7: Conclusions and Insights`

## Models Used
- **Random Forest (100 trees)**  
- **Voting Classifier** (Decision Tree + SVM + Neural Net)

Both models were evaluated using:
- Accuracy  
- F1 Score  
- Confusion Matrix  
- Train/Test performance gaps

## Results Summary

| Model                   | Test Accuracy | Test F1 Score |
|------------------------|----------------|----------------|
| Random Forest (100)     | 88.75%         | 0.8661         |
| Voting (DT + SVM + NN)  | 86.56%         | 0.843

Random Forest had slightly better performance overall but showed signs of overfitting. The Voting Classifier performed consistently with smaller gaps between training and test scores.

## Files
- `ensemble-davidrm.ipynb` – Full notebook with code, analysis, and results
- `winequality-red.csv` – The dataset used for training/testing

## Getting Started
### Clone the Repository

```bash
git clone https://github.com/drodmay1/applied-ml-davidrm.git
cd applied-ml-davidrm/lab05
```

### Set Up and Active Virtual Environment
# Create virtual environment
python -m venv .venv

# Activate on macOS/Linux
source .venv/bin/activate

# Or activate on Windows
.venv\Scripts\activate


