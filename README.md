# Tweet-Sentiment-Classification-using-Apache-Spark

  1. Project application done in Python using Apache Spark mllib libraries, to classify the tweets as positive or negative.
  2. Converted the tweet text and it's polarity as RDD.
  3. Preprocessing Steps:
    1. Lowercase all characters
    2. Stemming using Porter Stemmer
    3. Strip punctuations
    4. Replace two or more occurrences of the same character with two occurrences. i.e. ‘exciteddddd’ to ‘excitedd’
    5. Replace Hash tags, ex. #xyz with xyz
    6. Replace a word contains www. or http(s):// with URL
    7. Replace a word contains @someuser with AT_USER
    8. Ignore words that don’t start with an alphabet
    9. Ignore stop words
    10. Use html.unescape to replace html escape characters and replace with their meaning
    11. Replace aposthope characters apostrophes to standard lexicons 
  4. Used Naive Bayes, Logistic regression with Stochstic Gradient Descent and LBFGS, Decision Trees, SVM 
