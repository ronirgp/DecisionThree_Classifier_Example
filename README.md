### 📐 Evaluation Metrics from Handwritten Notes

- **Confusion Matrix Info**  
  - **TP = 5** (Predicted = 1, Actual = 1)  
  - **TN = 3** (Predicted = 0, Actual = 0)  
  - **FP = 0** (Predicted = 1, Actual = 0)  
  - **FN = 2** (Predicted = 0, Actual = 1)

---

#### 🧮 Formulas

1. **Accuracy**  
   \[
   \text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN} = \frac{5 + 3}{5 + 3 + 0 + 2} = \frac{8}{10} = 0.8
   \]

2. **Precision**  
   \[
   \text{Precision} = \frac{TP}{TP + FP} = \frac{5}{5 + 0} = 1.0
   \]

3. **Recall**  
   \[
   \text{Recall} = \frac{TP}{TP + FN} = \frac{5}{5 + 2} = \frac{5}{7} \approx 0.714
   \]

4. **F1 Score**  
   \[
   F1 = \frac{2 \cdot (\text{Precision} \cdot \text{Recall})}{\text{Precision} + \text{Recall}} = \frac{2 \cdot (1.0 \cdot 0.714)}{1.0 + 0.714} \approx \frac{1.428}{1.714} \approx 0.833
   \]
