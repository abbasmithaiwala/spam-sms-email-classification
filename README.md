# Spam SMS / Email Classification

This project implements a machine learning model to classify SMS messages or emails as spam or ham (non-spam) using the Multinomial Naive Bayes algorithm.

## Project Overview

The system analyzes the textual content of messages to determine the likelihood of them being spam. It utilizes natural language processing techniques and the Multinomial Naive Bayes classifier, which is particularly effective for text classification tasks.

### Features

- Text preprocessing and tokenization
- Feature extraction using bag-of-words or TF-IDF
- Implementation of Multinomial Naive Bayes classifier
- Model evaluation and performance metrics
- Easy-to-use interface for classifying new messages

## Requirements

- Python 3.7+
- NumPy
- Pandas
- Scikit-learn
- NLTK (Natural Language Toolkit)

## Model Performance

- Accuracy: 97%
- Precision: 100%


This project uses The UCI SMS Spam Collection dataset. It contains 5500 messages, labeled as spam or ham.

## How It Works

1. **Text Preprocessing**: Messages are cleaned, tokenized, and converted to lowercase. Stop words and punctuation are removed.
2. **Feature Extraction**: The bag-of-words model or TF-IDF is used to convert text into numerical features.
3. **Model Training**: The Multinomial Naive Bayes classifier is trained on the preprocessed data.
4. **Classification**: New messages are preprocessed and classified using the trained model.

## Future Improvements

- Implement more advanced feature extraction techniques like word embeddings
- Experiment with other algorithms (e.g., SVM, Random Forest) for comparison
- Develop a web interface for easy user interaction
- Implement real-time classification for email clients or SMS applications

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

For any questions or suggestions, please open an issue.
