Prodigy Infotech Task-1

House Price Prediction
This Python script demonstrates a simple linear regression model for predicting house prices using the scikit-learn library. It loads a dataset containing various features of houses (such as the number of bedrooms, bathrooms, living area square footage, etc.) along with their prices, trains a linear regression model on the training data, and evaluates its performance using mean squared error and R-squared metrics.

Getting Started
Prerequisites
Make sure you have Python installed on your system. You'll also need to install the following libraries:

pandas
matplotlib
seaborn
scikit-learn
You can install these libraries using pip:

Copy code
pip install pandas matplotlib seaborn scikit-learn
Usage
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/house-price-prediction.git
Navigate to the project directory:
bash
Copy code
cd house-price-prediction
Run the Python script:
Copy code
python house_price_prediction.py
Dataset
The dataset used in this project is stored in a CSV file named data.csv. It contains various features of houses (such as the number of bedrooms, bathrooms, living area square footage, etc.) along with their corresponding prices.

Model Evaluation
The script evaluates the performance of the linear regression model using two metrics:

Mean Squared Error (MSE)
R-squared (R2)
Results
After training the model and evaluating its performance, the script displays the following results:

Mean Squared Error
R-squared
Additionally, it generates two plots:

Actual Prices vs. Predicted Prices
Residual Plot
