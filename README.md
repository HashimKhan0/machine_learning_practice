# Machine Learning Practice

A collection of guided machine-learning projects that span classification, regression, time-series forecasting, NLP and recommender systems. Each project is a self-contained Jupyter notebook.

## Projects

| Project | Task | Approach |
|---|---|---|
| [CIFAR-10 classification](CIFAR10_clssificaiton/) | Image classification (10 classes) | Convolutional neural network (Keras) with data augmentation; theory notes in `THEORY.md` |
| [Traffic sign classification](traffic_sign_classification/) | Image classification | CNN (Keras), evaluated with a confusion matrix |
| [Car purchasing](car_purchasing/) | Regression: predict how much a customer will spend on a car | Feed-forward neural network (Keras) with Min-Max scaling |
| [Avocado market](avocado_market_prediction/) | Time-series forecasting of avocado prices | Facebook Prophet |
| [Chicago crime](chicago_crime/) | Time-series forecasting of crime counts | Facebook Prophet |
| [Yelp reviews](NLP_yelp_reviews/) | Sentiment / rating classification from review text | NLTK preprocessing, bag-of-words, Multinomial Naive Bayes |
| [Email spam filter](email_spam_classification/) | Spam vs. ham classification | Bag-of-words and Multinomial Naive Bayes |
| [Movie recommender](movie_reccomender_system/) | Item-based recommendations | Correlation between user rating vectors |

## Running

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow prophet nltk
jupyter notebook
```

## Tech stack

Python · TensorFlow / Keras · scikit-learn · Prophet · NLTK · pandas · NumPy · matplotlib / seaborn
