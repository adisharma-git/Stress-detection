# 🌟 Stress Detection Using Naïve Bayes Classifier  

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Na%C3%AFve%20Bayes-blue)  
![Python](https://img.shields.io/badge/Python-3.8+-yellow)  
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)  

## 🚀 Overview  
This project focuses on **stress detection** using **Natural Language Processing (NLP)** and the **Naïve Bayes classification algorithm**. It analyzes textual data from the `stress.csv` dataset and predicts whether a given text indicates stress.  



---

## 📊 Dataset  
- The `stress.csv` dataset contains **textual data** related to stress.  
- It is preprocessed and vectorized before applying machine learning algorithms.  

---

## 🔥 Features  
✅ **Text Preprocessing:**  
   - Converts text to lowercase  
   - Removes stopwords and punctuation  
   - Applies lemmatization  

✅ **Feature Engineering:**  
   - Converts text into numerical format using **TF-IDF (Term Frequency-Inverse Document Frequency)**  

✅ **Machine Learning Model:**  
   - Uses the **Naïve Bayes classifier** for stress classification  

✅ **Prediction System:**  
   - Takes user input for **real-time stress detection**  

---

## ⚙️ Installation & Setup  
Ensure you have the required dependencies installed. Run the following command:  

```bash
pip install pandas numpy scikit-learn nltk

```

To download required NLTK data, run:
```bash
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
```


📈 Future Enhancements
🔹 Experiment with Logistic Regression, Random Forest, or Deep Learning for better accuracy.
🔹 Build a web interface for real-time stress detection.
🔹 Expand the dataset for more robust predictions.




⭐ If you found this project helpful, please give it a star ⭐ on GitHub!
