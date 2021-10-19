# Pattern-Recognition

**ABSTRACT
Recommender systems are one of the most popular and successful applications of modern data machine learning technologies. In particular, coupon recommendation systems, such as Groupon and Honey, can enhance customers’ engagement with businesses and increase the likelihood of the customer to return often. The customer is often looking for convenience and ease of use of any system. Because of that, the focus of this project is in-vehicle coupon recommendation systems. In-vehicle recommendation systems aim to conveniently supply the right coupons based on preferences of the user and by taking available context information into account. This information consists of the user’s current driving situation, such as the destination, current time, weather, passengers, etc. However, the challenge is getting to know the customer and deciding which coupons to recommend. This task can be complex because a single brand can have thousands of customers, each of whom responds to coupon offers differently depending on the attributes presented in their customer profile. To solve this complex task, we will use various machine learning classification techniques to predict a user’s response to a coupon recommendation based on their user profile or similarities to other user’s profile using an in-vehicle coupon recommendation system dataset that consists of 12684 instances. This dataset was downloaded from the UCI Machine Learning Repository (Bache and Lichman, 2013). Feature selection methods and supervised learning classifier models with different hyperparameters were used to train the data. The best accuracy achieved among five different classifier models was a 71 percent, while the best precision was a 72 percent. These results suggest that we have “High Bias” in our models. In other words, our model is underfitting our example dataset and it is not presenting an accurate representation of the relationship between input and predicted output. For better accuracy and precision, a boosting algorithm called CatBoost was used for gradient boosting on decision tree classifiers to overcome the underfitting problem. The accuracy result was 94.7 percent, while the precision was 94 percent, with 96 percent recall and 99 percent Area Under the ROC Curve (AUC). 

**Key Words
Coupon purchase, Sales recommendation System, Machine Learning, Categorical data mining, Gradient boosting technique, classification. 
