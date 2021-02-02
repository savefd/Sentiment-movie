# Sentiment Analysis with Logistic regression
Sentiment Analysis on Movie Reviews

Data: IMDB 50k movie reviews

the MovieReview.ipynb contains these important functions for logistic regression
1. process -> text preprocessing function
2. frequency_count -> generate frequency dictionary
3. extractFeature -> get array with shape (1,3) > (constant, sum_positive, sum_negative)
4. sigmoid function and gradientDescent for Logistic regression
5. train_model -> prepare x and y, then using gradient descent to optimize theta
6. Predict -> Predict individual review
7. model_acc_test -> get model accuracy on testdata
