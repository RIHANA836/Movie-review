# 🎬 Movie Review Sentiment Analysis Using LSTM

## 📌 Project Overview  
This project utilizes **Long Short-Term Memory (LSTM)** networks to classify movie reviews as **positive or negative** based on sentiment.  

## 📊 Dataset  
- **Review**: Contains movie reviews  
- **Sentiment**: Binary values (**0 for negative, 1 for positive**)  

## 🔧 Technologies & Libraries Used  
- **Python**, with:  
  - **Pandas** and **NumPy** for data manipulation  
  - **Seaborn** and **Matplotlib** for visualization  
  - **NLTK** for text preprocessing  
  - **TensorFlow** and **Keras** for deep learning  
  - **Scikit-learn** for model evaluation  

## 🔄 Preprocessing Steps  
- Removed special characters and stopwords  
- Tokenized and lemmatized text  
- Converted text to sequences and applied padding  
- Split dataset into **training (70%)** and **testing (30%)**  

## 🤖 Model Architecture  
- **Embedding Layer**: Converts words into vector representations  
- **LSTM Layers**: Captures sequential dependencies  
- **Dropout Layers**: Reduces overfitting  
- **Dense Layers**: Predicts sentiment using **sigmoid activation**  

## 📈 Results & Evaluation  
- **Accuracy** evaluated on test data  
- **Confusion matrix** visualization  
- **Classification report** with precision, recall, and F1-score  

## 📚 Conclusion  
This project demonstrates how **LSTMs** can effectively classify sentiment in text data, making them powerful for **NLP applications**.  
