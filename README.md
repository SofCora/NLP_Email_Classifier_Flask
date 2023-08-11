# NLP_Email_Classifier_Flask
Coverted raw email text metadata into numeric form using a count vectorizer then fed it into a logistic regression model to determine whether the email was spam or legitimate

This project was first done through the JPMorgan Cybersecurity Virtual Experience Program then I decided to expand upon it and practice implementing my models in a user friendly way, it was inspired by the work I do at my infosec internship which involves manually reviewing emails people send to IT and determining whether they are phishing messages or not

Using scikit learn, I was able to develop a machine learning model that classified emails into two categories. First, I had to preprocess the dataset so that it was in a format that the model could be trained on. Then, I selected the appropriate classifier for the task at hand. Finally, I analyzed statistics on my dataset then trained my logreg model.

I then implemented this model into a web application framework using flask so that it would take in user input and predict whether the email was spam or ham
