# Iris-Flower-Classification
## Dataset:
The dataset used in this project focuses on classifying iris flowers into three species: Iris-setosa, Iris-versicolor, and Iris-virginica. It contains 150 samples, with each species represented by 50 samples. Each flower is described by four key features: sepal length, sepal width, petal length, and petal width. These measurements vary across species, making classification possible based on these characteristics.
Although the Scikit-learn library provides a built-in Iris dataset, an alternative version was also available for use. The task was to train a machine learning model that could accurately classify the species of iris flowers based on their measurements.
Exploratory Data Analysis (EDA):
To gain insights into the dataset, I performed exploratory data analysis (EDA), using visualizations like pairplots to explore the relationships between the features and species. Additionally, I analyzed the distribution of the flower species to ensure the dataset was balanced, which is critical for training the model.
## Model:
I implemented the K-Nearest Neighbors (KNN) algorithm for this classification task due to its simplicity and effectiveness. KNN works by identifying the 'k' nearest data points in the feature space and predicting the species based on the majority vote of these neighbors. After experimenting with different values of 'k', the model achieved a high accuracy of 98 %.
To improve the performance of the model, I applied feature scaling to normalize the ranges of the features. The model was evaluated by splitting the dataset into training and test sets, ensuring robust performance.
## Conclusion:
This project provided valuable experience in building a machine learning classification model, exploring data through EDA, and optimizing model performance. With a final accuracy of 98 %, the KNN model proved highly effective in classifying iris flower species based on their measurements.
