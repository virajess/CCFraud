# Enhancing Credit Card Fraud Detection Using Machine Learning: A Comparative Analysis of SVM and MLP

Writers:
- Jonathan David
- Vira Jessica

Card fraud leads to substantial financial losses, making accurate detection crucial. This study analyzes a Kaggle dataset of 284,807 European credit card transactions from 2013 to compare Support Vector Machine (SVM) and Multilayer Perceptron (MLP) models for fraud detection. A sensitivity analysis is conducted to assess financial impacts, highlighting the importance of precise fraud detection in minimizing economic losses.

Our data preprocessing involved several key steps to ensure model effectiveness. The dataset, already preprocessed with PCA and label encoding (0 for non-fraud, 1 for fraud), was first checked for null and duplicate values. We then applied undersampling to balance the class distribution and split the data into training and testing sets.

In this project, we tested the performance of two classification models, Support Vector Machine (SVM) and Multilayer Perceptron (MLP), for credit card fraud detection. The training data was divided using 10-fold cross-validation to ensure robust evaluation. For each fold, accuracy, precision, recall, F1-score, and AUC-ROC were recorded for both models. After cross-validation, the entire training dataset was used to train both models again, and the same evaluation metrics were obtained to assess their overall performance.

In this project, we tested the performance of two classification models, Support Vector Machine (SVM) and Multilayer Perceptron (MLP), for credit card fraud detection. The training data was divided using 10-fold cross-validation to ensure robust evaluation. For each fold, accuracy, precision, recall, F1-score, and AUC-ROC were recorded for both models. In terms of AUC-ROC, MLP outperformed SVM. Additionally, a t-test was conducted to determine whether the difference in AUC-ROC scores between the two models was statistically significant, and the results showed no significant difference. After cross-validation, both models were trained again on the entire training dataset, and the same evaluation metrics were obtained. Once again, MLP demonstrated significantly better performance compared to SVM.

Finally, a sensitivity analysis was conducted using Monte Carlo simulation based on the false positive and false negative rates of the best-performing model, MLP. The estimated potential losses calculated using the model’s prediction error rates highlights the importance of developing an accurate fraud detection model to minimize financial risks. The results of this research are thoroughly documented in this [paper](https://drive.google.com/drive/folders/1xhznG_LYTp7lryzm9tbP6K_WNHZ3MXd0?usp=sharing).
