Credit Card Fraud Detection

In this project I predict fraudulent credit card transactions using machine learning. 
In the repository I'm including a smaller balanced dataset (df_balanced.csv) for experimentation rather than the initial dataset that I cleaned. The initial dataset is from the following source here: https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud/data 

I used logistic regression to create a fast Benchmark model acheiving an F1 of ~0.95. I then tried a gradient boosted classifier and got an accuracy of ~99%. I've evaluated the model using accuracy, precision, recall, F1-score, and ROC AUC and considered model speed vs. accuracy for real-time deployment.
