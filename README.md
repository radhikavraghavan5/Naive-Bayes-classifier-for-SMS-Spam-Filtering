# Naive-Bayes-classifier-for-SMS-Spam-Filtering

Building a Spam Filter with Naive Bayes
[Originally published on Towards Data Science](https://towardsdatascience.com/how-to-build-and-apply-naive-bayes-classification-for-spam-filtering-2b8d3308501)

<img width="495" alt="Screenshot 2023-02-27 at 10 40 17 PM" src="https://user-images.githubusercontent.com/56044346/221774401-0c8f478a-172c-453c-80b4-8f14e63301cf.png">


# Scope
This project aims to build a Spam Filter using R libraries, which classifies new messages as spam or ham, by utilizing the Naive Bayes classifier. Its accuracy aims for a ratio of above 90%

# Scenario
This challenge was part of the Data Science course I studied, goal was to provide the contest with an algorithm, that takes as input the user's sms and automatically filters out the spam ones. This algorithm would be implemented to a new app and should score an accuracy ratio of at least 90% (the standard one achieved by the competitors).

# Data Sets
To train the algorithm, I used a dataset of 5560 SMS messages that are already classified by humans.

# Roadmap
Briefly explore the full data set, consisting of 5560 SMS messages, which is distributed among spam and ham content by approximately 87% and 13%, respectively.

I divided the dataset into two sub-sets, opting for a 75% — 25% split-up:

- training_set: used to “train” the computer how to classify messages
- test_set: used to finally test how good the spam filter is (accuracy)

I then pre-processed them by using recipe by normalizing and scaling and used knn imputation to impute missing values. With this I was able to Extract the necessary Features, just so I feed the model with meaningful data and train it.

Finally, we evaluate the model by measuring its classification accuracy as the percentage of succesfully labeled SMS.

# Conclusion
I managed to manipulate hundreds of SMS texts, preprocessed them effectively and encoded them into numeric vectors. As a result, I managed to train the model and provide 93% accuracy, fair above the initial target of 90%.

