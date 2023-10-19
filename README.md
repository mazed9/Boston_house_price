## Boston_house_price_prediction

### Software and Tools Requirements

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com)
3. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)


### Create a new environment
'''
conda create -p venv python==3.7 -y
'''

### Machine Learning
1. [Download Boston House Price dataset](https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data)
2. Perform Exploratory Data Analysis.
3. Scale the data.
4. Pickle the scaler to use later when  making prediction from the app to scale the input data.
5. Split the dataset into train and test set.
6. Train linear regression model.
7. Make prediction on test data.
8. Pickle the trained model.


### House Price Prediction in Web Application & API
This project offers two methods to predict house prices in Boston:

1. A web-based user interface.
2. A dedicated API endpoint for programmatic access.

### Web-Based User Interface
![Alt text](<Screenshot 2023-10-20 014522.png>)

#### How to Use:
* Navigate to the home page .
* Fill in the required fields with the data necessary for prediction.
* Click the "Predict" button.
* The prediction for the house price will be displayed on the same page.


### API Endpoint for Predictions
Endpoint Details:
* URL: '/predict_api'
* Method: Post
* Request Payload: JSON object with house features.
* Response: The response will be a JSON containing the predicted house price.