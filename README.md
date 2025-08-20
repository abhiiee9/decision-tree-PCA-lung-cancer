# End-Term Practical: Decision Tree Classification with PCA

## Task
Perform classification using a Decision Tree (DT) on the provided **Lung Cancer dataset**, and apply **Principal Component Analysis (PCA)** for dimensionality reduction. Compare the performance before and after PCA.

---

## Steps Implemented
1. **Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Scaled features
   - Split data into training (80%) and testing (20%)

2. **Baseline Decision Tree**
   - Trained a Decision Tree classifier
   - Evaluated using Accuracy, Precision, Recall, F1-score
   - Plotted Confusion Matrix
   - Checked feature importance

3. **PCA + Decision Tree**
   - Applied PCA retaining ≥95% variance
   - Retrained Decision Tree on PCA-transformed data
   - Compared results with baseline

4. **Discussion**
   - Baseline DT feature importance showed which features had the highest impact
   - PCA reduced dimensionality, improving training efficiency
   - Performance was compared before vs after PCA

---

## Results
- **Baseline DT**: Provided feature importance and reasonable accuracy.  
- **DT with PCA**: Reduced features while maintaining comparable accuracy.  
- PCA made the model simpler, with only minor trade-offs in interpretability.  

---
