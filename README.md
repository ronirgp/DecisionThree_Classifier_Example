## 📊 Evaluation Metrics from Handwritten Notes

### Confusion Matrix Info
- **TP = 5** (Predicted = 1, Actual = 1)
- **TN = 3** (Predicted = 0, Actual = 0)
- **FP = 0** (Predicted = 1, Actual = 0)
- **FN = 2** (Predicted = 0, Actual = 1)

---

### 📐 Formulas

1. **Accuracy**  
   Accuracy = (TP + TN) / (TP + TN + FP + FN)  
   Accuracy = (5 + 3) / (5 + 3 + 0 + 2) = 8 / 10 = **0.8**

2. **Precision**  
   Precision = TP / (TP + FP)  
   Precision = 5 / (5 + 0) = **1.0**

3. **Recall**  
   Recall = TP / (TP + FN)  
   Recall = 5 / (5 + 2) = 5 / 7 ≈ **0.714**

4. **F1 Score**  
   F1 = 2 × (Precision × Recall) / (Precision + Recall)  
   F1 = 2 × (1.0 × 0.714) / (1.0 + 0.714) ≈ **0.833**
