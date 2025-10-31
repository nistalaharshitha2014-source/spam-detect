# 📨 Spam Email Detection using Multinomial Naive Bayes

This project detects whether an email message is **spam or ham (non-spam)** using **machine learning** techniques. The model is built using the **Multinomial Naive Bayes classifier**, a popular algorithm for text classification tasks such as spam filtering.

## 🚀 Key Features
- Preprocessing of email text (lowercasing, removing symbols, stopwords, and applying stemming)
- TF-IDF vectorization to convert text into numerical features
- Training and testing of the Multinomial Naive Bayes model
- Model evaluation using accuracy, confusion matrix, and classification report
- Visualization of spam vs ham message distribution
- Prediction of new unseen email messages

## 🧠 Technologies Used
- Python  
- Pandas, NumPy  
- NLTK for text preprocessing  
- Scikit-learn for model building  
- Matplotlib & Seaborn for visualization  

## 📊 Workflow
1. Load and clean the dataset  
2. Convert text into numerical vectors using TF-IDF  
3. Train the Multinomial Naive Bayes classifier  
4. Evaluate model performance  
5. Predict and classify new email messages  

## 🧾 Outputs
- Trained model: `spam_model.pkl`  
- Vectorizer: `model vectorizer.pkl`  
- Visualizations of spam/ham distribution  

## ▶️ How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/spam-email-detection.git
cd spam-email-detection

# Install dependencies
pip install -r requirements.txt

# Run the script
python spam_email_detection.py
```

## 📈 Example Predictions
| Message | Prediction |
|----------|-------------|
| "Congratulations! You have won a free ticket." | Spam |
| "Hi John, are we meeting for lunch tomorrow?" | Ham |

---
**Author:** Nistala Harshitha  
