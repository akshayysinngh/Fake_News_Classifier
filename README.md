This project focuses on the task of fake news detection by employing the use of stemming techniques and a 
Random Forest model. The aim is to build a classifier that can effectively distinguish between fake news and 
genuine news articles based on their titles.

The dataset provided for this project consists of news pairs, each containing a fake news title (title1_en) and 
a corresponding news title (title2_en). The dataset is labeled with three categories indicating the relationship 
between the news pairs: agreed, disagreed, or unrelated. The task is to develop a machine learning model that 
can predict the relationship label for the test data, which does not contain any labels.

To preprocess the data, stemming techniques were applied to the news titles. Stemming helps reduce the words 
to their base or root form, which can improve the model's ability to identify similar words with different forms. 
By reducing words to their stems, the model can capture the core meaning and essence of the titles more effectively.

For the classification task, a Random Forest model was chosen. Random Forest is an ensemble learning method 
that combines multiple decision trees to make predictions. It is known for its ability to handle 
high-dimensional data and avoid overfitting. The model was trained on the provided training data, 
which includes the labeled news pairs, and the performance was evaluated using the validation data.
