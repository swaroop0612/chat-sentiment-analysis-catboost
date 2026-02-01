# Chat-Based Sentiment Analysis Using CatBoost
This project focuses on building a chat-based sentiment analysis system using the CatBoost machine learning algorithm. 
It classifies short and informal chat messages into positive, neutral, or negative sentiments.

🔹 Features
- Handles short, informal chat messages
- Emoji-aware text preprocessing
- CatBoost model with native text handling
- Balanced sentiment classification
- Real-time sentiment prediction
- Extensive data visualization and evaluation
  
🔹 Dataset
- Self-created dataset with 6000+ chat messages
- Sentiment labels: Positive, Neutral, Negative
- Includes emojis, slang, and noisy chat text

🔹 Model Used
- Algorithm: CatBoostClassifier
- Loss Function: MultiClass
- Evaluation Metric: Accuracy
- Handles text features directly without TF-IDF

🔹 Visualizations
- Sentiment class distribution
- Chat message length distribution
- Emoji usage across sentiments
- Training vs validation accuracy
- Confusion matrix

🔹 Results
- Accuracy: ~75%
- Balanced precision, recall, and F1-score across classes
- Robust performance on noisy chat data

🔹 Future Improvements
- Sarcasm detection
- Multilingual sentiment analysis
- Deep learning models (LSTM, BERT)
- Web interface deployment
