#Text Representation

Since machine learning models cannot directly process raw text, the messages were converted into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency).
TF-IDF assigns importance scores to words based on how frequently they appear in a message while reducing the importance of very common words across the dataset. This allows the models to capture meaningful patterns from the text data

#Model Performance Summary

After completing the data preprocessing steps and training different models, their performances were compared.

The first model (Logistic Regression) achieved the best results among the tested models and showed a reliable performance on the dataset.
The third model (Random Forest Classifier) also improved after the adjustments and performed better than its initial version. However, it still could not outperform the first model (Logistic Regression).

Overall, Logistic Regression was the most suitable model for this problem, while Random Forest showed that it can achieve better results with further tuning and optimization.

<img width="531" height="171" alt="image" src="https://github.com/user-attachments/assets/57065dcf-8b2d-439a-b1f2-bdbe36b19e4e" />

