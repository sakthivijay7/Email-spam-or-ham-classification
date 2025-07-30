# Email-spam-or-ham-classification
#### Date:July30 -2025
- Data colletion:
  Data collected from kaggle name of dataset email.csv
- Data Handling:
  Python ``pandas`` to read the csv file and check null values .
- Data split:
  Features - x_train ``75%``,x_test ``25%``.
  Target - y_train ``75%``,y_test ``25%``.
- Data Preprocessing:
``NLTK`` to clean the texts columns like remove stopwords and used regex ``[^a-z\s] without alphabets and space characters to be removed.
and map ``ham:1,spam:0``
- Feature extraction:
  ``TfidfVectorizer`` to encoding the texts columns.
- Algorithm:
  Naive_bayes - ``MultinomialNB`` to train the model.
- Model and Tokens save:
  Tokenizing and trained model to saved in ``pickle`` file for future prediction.
- cross_val_Score:
  Model got cross validation score ``97%``with cross value=5.
- Result:
  Model acheived ``98%`` for classify the email has ham or spam.

- Techniques:
  Python [``pandas,re,sklearn,pickle,numpy,nltk``],
  Jupyter notebook,
  vs code

