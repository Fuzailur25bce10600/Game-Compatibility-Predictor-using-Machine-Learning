# 🎮 PC Game Compatibility Prediction using Machine Learning

## Overview
Determining whether a PC can run a game requires manually comparing system specifications, which can be time-consuming and confusing. This project uses machine learning to predict **game compatibility** based on minimum system requirements.

Due to structured hardware specifications and dataset limitations, the problem was formulated as a **binary classification task**.

---

## Dataset
**Source:** PC Game Requirements Dataset by Baraa Zaid  
- Contains minimum system requirements for PC games  
- Includes RAM, CPU, GPU, File Size, and OS  
- Around 80,000 game entries  
- Unstructured and inconsistent formatting  

---

## Approach
- Cleaned and structured system requirement data  
- Extracted numerical values from hardware specifications  
- Converted problem from regression to classification  
- Created compatibility labels (0 = Not Compatible, 1 = Compatible)  
- Handled class imbalance and prediction bias  
- Trained a Decision Tree Classifier  
- Applied threshold tuning for balanced performance  

---

## Results
Accuracy: **89.98%**  
Precision: **0.90**  
Recall: **0.90**  
F1-Score: **0.90**  
<img width="555" height="201" alt="metrics" src="https://github.com/user-attachments/assets/c388d85f-0bdb-4c42-9a83-c43da6cd720b" />



The model achieves **balanced performance** across both compatibility classes while maintaining reliable predictions.

---

## Example Prediction



# Output
Prediction: 1 (Compatible)
Confidence: 0.89
<img width="472" height="256" alt="recommendation list" src="https://github.com/user-attachments/assets/c78bce37-cd59-4c48-b8c0-00ed5443e6e4" />
