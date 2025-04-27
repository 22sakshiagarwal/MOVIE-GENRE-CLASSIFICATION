

# 🎬 Movie Genre Classification Using NLP

This project focuses on **predicting movie genres** based on plot summaries using advanced **Natural Language Processing (NLP)** techniques.  
We utilize **TF-IDF vectorization** and a **Multinomial Naive Bayes classifier** to build an efficient, lightweight model that categorizes Indian movies into their respective genres.

---

## 📁 Project Structure

| File | Description |
|:-----|:------------|
| `Movie Genre Classification.ipynb` | Jupyter Notebook containing the complete data preprocessing, model training, and evaluation pipeline. |
| `Indian_movies.csv` | Dataset containing Indian movie titles, plot summaries, and genres for training and testing. |

---

Technologies & Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
---

 Approach

1. Data Loading and Cleaning
   - Load movie data
   - Remove missing or irrelevant entries
   - Clean plot summaries (lowercasing, removing punctuations, etc.)

2. Feature Engineering  
   - Apply **TF-IDF Vectorization** to transform plot summaries into numerical vectors.

3. Model Training 
   - Train a **Multinomial Naive Bayes** classifier on the processed data.

4. Model Evaluation 
   - Evaluate using metrics like Accuracy, Precision, Recall, and F1-Score.
   - Visualize results with a Confusion Matrix.

5. Genre Prediction 
   - Predict genres for new/unseen movie plots.

---

##  Future Enhancements

- Experiment with more advanced models like **Random Forest**, **Support Vector Machine (SVM)**, or **Deep Learning** architectures.
- Perform **hyperparameter tuning** for better performance.
- Expand the dataset with more diverse movies.
- Deploy the model using **Streamlit**, **Flask**, or **FastAPI**.
- Incorporate **Explainable AI (XAI)** methods like LIME/SHAP for interpretation.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

##  Acknowledgments

- Inspired by the growing importance of NLP in entertainment industry analytics.
- Dataset sourced from publicly available Indian movie databases.

---

### Tags
`NLP` `TF-IDF` `Naive Bayes` `Movie Genre Classification` `Indian Cinema` `Machine Learning` `Text Classification`

---



