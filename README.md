# Suicide-Ideation-Detection-Using-NLP-Ensemble-Learning

In this notebook, we build a Suicide Ideation Detection system using Natural Language Processing (NLP) and Machine Learning techniques. The dataset consists of social media posts labeled as either suicidal or non-suicidal.

We begin with data preprocessing, including text cleaning, normalization, and exploratory data analysis (EDA) to better understand the dataset. The textual data is then converted into numerical features using TF-IDF vectorization.

To classify the posts, we train multiple machine learning models, including Gaussian Naive Bayes, Bernoulli Naive Bayes, and Multinomial Naive Bayes. These models are combined using a soft Voting Classifier to improve overall prediction performance.

Finally, we evaluate the model using metrics such as the confusion matrix and classification report, and save the trained model for future inference on new text inputs. The goal is to accurately identify potentially suicidal content and support early intervention efforts.
