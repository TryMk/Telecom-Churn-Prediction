
## 🧠 Techniques Used

- **Libraries**: NumPy, Pandas, Scikit-Learn, TensorFlow/Keras, Matplotlib, Seaborn
- **Preprocessing**:
  - Missing value handling
  - One-Hot Encoding
  - SMOTE for class imbalance
  - Train-Test Split (80-20)
- **Model**: Feedforward Neural Network (MLP)
  - Input → Dense(64, ReLU) → Dropout(0.3) → Dense(32, ReLU) → Dropout(0.3) → Output(Sigmoid)
- **Evaluation**:
  - Accuracy: **80.4%**
  - AUC: **0.842**
  - Confusion Matrix, Precision, Recall, F1-score

## 📊 Results Summary

| Metric        | Churned (Class 1) | Not Churned (Class 0) |
|---------------|-------------------|------------------------|
| Precision     | 0.60              | 0.89                   |
| Recall        | 0.61              | 0.89                   |
| F1-score      | 0.60              | 0.89                   |
| AUC           | \> 0.84           | —                      |

![ROC Curve](./visuals/roc_curve.png)
![Confusion Matrix](./visuals/confusion_matrix.png)
