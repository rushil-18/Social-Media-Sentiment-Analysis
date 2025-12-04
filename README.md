# Social-Media-Sentiment-Analysis
📖 Project Overview

This project focuses on analyzing customer sentiments from Amazon product reviews using Natural Language Processing (NLP) techniques.
Each review is classified into one of the 3 sentiment categories:

😊 Positive

😐 Neutral

😡 Negative

We trained a Multinomial Naive Bayes classifier with TF-IDF textual features.

🗂 Dataset

Source: Amazon Product Reviews Dataset (Open Source)

Size Used: 50,000 reviews

Columns:

Text → Customer review content

Score → Review rating (1–5)

Sentiment (Generated) → Positive/Neutral/Negative based on Score

Sentiment Labeling Rule:

Score	Sentiment
4 & 5	Positive
3	Neutral
1 & 2	Negative
⚙️ Technologies & Libraries Used
Area	Tools
Programming	Python
Notebook	Google Colab
NLP	TF-IDF Vectorizer
ML Algorithm	Multinomial Naive Bayes
Visualization	Matplotlib, Seaborn
📊 Model Performance
Metric	Result
Accuracy	~74.6% (with 10K dataset)
Accuracy (Expected with 50K dataset)	Better performance

Model Output Examples:

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix Visualization

User Input Review Prediction

✨ Features

✔️ Preprocessing of text data
✔️ Automated sentiment labeling
✔️ TF-IDF text vectorization
✔️ Sentiment classification model
✔️ User input: Enter a review → Get sentiment prediction
✔️ Visual representations & evaluation metrics

🚀 How To Run

1️⃣ Upload the dataset to Google Colab → /content/
2️⃣ Run all notebook cells sequentially
3️⃣ Enter your own review and test the sentiment prediction

🔮 Future Enhancements

Implement deep learning model (LSTM/BERT) for higher accuracy

Improve neutral and negative classification

Deploy model as a Web App / Streamlit UI

📌 Conclusion

This project provides a complete pipeline for real-world sentiment analysis on e-commerce product reviews. It helps companies understand user opinions and improve business strategies.
