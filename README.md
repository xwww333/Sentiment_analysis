# Sentiment_analysis
A machine learning app that analyzes the sentiment of financial analyst reports and detects potential bias in tone. It uses NLP techniques to classify report sentiment and assess whether analysts consistently lean positive or negative beyond expected norms.

This project is a machine learning application that analyzes the sentiment in financial analyst reports and investigates whether the tone used by analysts shows signs of systematic bias.

Financial analyst reports often influence investor behavior and market movements. However, the tone in these reports can be subtly biased—intentionally or unintentionally—toward optimism or pessimism, depending on various incentives or institutional affiliations. This project aims to shed light on that.

Using Natural Language Processing (NLP) techniques, the app performs two main tasks:
Sentiment Classification: Determines whether the tone of a report is positive, neutral, or negative.
Bias Detection: Measures whether the sentiment deviates from expected norms, helping detect potential bias in how analysts communicate company performance or forecasts.

The model is trained on a labeled dataset of analyst reports and financial texts, and it incorporates both traditional NLP features and transformer-based models (e.g., BERT or FinBERT) for better context understanding.
