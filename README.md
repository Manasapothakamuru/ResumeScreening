This project focuses on predicting the categories of resumes using Natural Language Processing (NLP) techniques and a machine learning classifier. The dataset used contains various resumes categorized into different job fields.

Exploratory Data Analysis (EDA):
Visualized the distribution of resume categories using bar plots and pie charts.
Explored insights into the frequency distribution of job categories.

Data Preprocessing:
Cleaned the resume text by removing URLs, mentions, hashtags, and punctuations.
Utilized Label Encoding to convert categorical 'Category' labels into numerical format.

Text Vectorization:
Applied TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert cleaned resume text into numerical features.
Used a TfidfVectorizer with sublinear term frequency, English stop words, and a maximum of 1500 features.

Model Training:
Split the dataset into training and testing sets.
Employed a One-vs-Rest strategy with a K-Nearest Neighbors (KNN) classifier for multi-class classification.

Model Evaluation:
Evaluated the model's accuracy on both the training and test sets.
Generated a classification report to assess precision, recall, F1-score, and support for each category.

Dependencies
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
SciPy
