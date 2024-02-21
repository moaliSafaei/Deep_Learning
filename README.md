# Deep_Learning

## Housing Prices prediction using a simpe MLP
In this example, housing prices prediction was addressed by using a simple MLP network.
The dataset comprises various features related to housing, including the crucial “Price” column. Let’s break down the steps involved:

### Data Preprocessing:
Before training the model, the data needs to be preprocessed.
This involves splitting the dataset into training and testing subsets. I allocate 80% of the data for training and 20% for testing.
Additionally, I apply the MinMaxScaler function to normalize the features, ensuring consistent scaling across all variables.

#### Data Collection and Exploration:
A dataset of housing prices was used including features such as square footage, number of bedrooms, location, etc. 
Next, I explore the dataset, checking for missing values, outliers, and potential correlations.

#### Correlation Matrix:
Constructing a correlation matrix helps us understand the relationships between different features. It provides insights into which variables influence housing prices the most.
By visualizing the matrix, strong positive or negative correlations can be identified.

### Neural Network Architecture:
The network consists of two hidden layers, each with an arbitrary number of neurons.
I choose the Rectified Linear Unit (ReLU) activation function for its effectiveness in handling non-linearities.
Also, the optimizer is set to Stochastic Gradient Descent (SGD).

#### Hyperparameters:
Different hyperparameters were investigated to optimize our model’s performance.
Two learning rates are adopted: 0.1 and 0.001.
Foo each earning rate, 2 different number of epochs (NoP) was considered: 20 and 4000 number of epochs.

### Toolset:
To implement our model, we rely on Keras for building the neural network architecture.
Also, the whole model is written with Jupyter notebook. 
numpy was used for Algebraic calculations. 
pandas was used to deal with csv files. 
Matplotlib and Seaborn were utilized for chats and graphs.
tensorflow and sklearn were used for architecting the network.
In summary, this example demonstrates the essential steps in predicting housing prices. By following these procedures and fine-tuning the model, we can make accurate predictions and enhance decision-making in real estate markets.
