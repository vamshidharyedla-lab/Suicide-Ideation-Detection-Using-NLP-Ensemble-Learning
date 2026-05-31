# Suicide-Ideation-Detection-Using-NLP-Ensemble-Learning

In this notebook, I build a Suicide Ideation Detection system using Natural Language Processing (NLP) and Machine Learning techniques. The dataset consists of social media posts labeled as either suicidal or non-suicidal.

I start with data preprocessing, including text cleaning, normalization, and exploratory data analysis (EDA) to better understand the dataset. The textual data is then converted into numerical features using TF-IDF vectorization.

To classify the posts, I train multiple machine learning models, including Gaussian Naive Bayes, Bernoulli Naive Bayes, and Multinomial Naive Bayes. These models are combined using a soft Voting Classifier to improve overall prediction performance.

To enhance the reliability of the system, I evaluate the models using performance metrics such as accuracy, precision, recall, F1-score, confusion matrix, and classification reports. Special attention is given to correctly identifying potentially suicidal content, as this is critical in real-world applications.

Finally, I save the trained model and vectorizer for future inference on new text inputs. The goal of this project is to accurately identify potentially suicidal content and demonstrate the practical application of NLP and machine learning techniques in mental health-related text classification.





---

> **⚠️ NOTE:** GitHub may not be able to render this notebook correctly due to its size and output content. To view the complete project, please download `SuicideldeationDectection.ipynb` and open it locally using Jupyter Notebook, Jupyter Lab, VS Code, or Google Colab.

---
