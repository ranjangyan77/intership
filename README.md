📊 Telecom Customer Churn Prediction
This project aims to predict customer churn in a telecom company using a neural network model. The model is trained on a cleaned and preprocessed dataset and evaluated using classification metrics.

🚀 Features
Data cleaning and preprocessing

One-hot encoding of categorical features

Neural network built using Keras (Sequential API)

Evaluation using confusion matrix and classification report

Accuracy plots for training and validation

🧠 Technologies Used
Python

Pandas

NumPy

Matplotlib

Scikit-learn

Keras (TensorFlow backend)

📁 Dataset
The dataset is sourced from YBI Foundation GitHub and loaded via:

python
Copy
Edit
url = 'https://raw.githubusercontent.com/YBIFoundation/Dataset/refs/heads/main/TelecomCustomerChurn.csv'
⚙️ How It Works
Load the dataset and preprocess it:

Drop customerID

Handle missing values

Convert categorical variables to dummy variables

Split the dataset into train and test sets.

Normalize the data using StandardScaler.

Define a neural network with:

Input layer matching feature size

Two hidden layers (32 and 16 neurons)

Output layer with sigmoid activation for binary classification

Train the model and evaluate on test data.

Visualize training and validation accuracy over epochs.

📈 Model Performance
Accuracy printed after model evaluation

Confusion matrix and classification report displayed

Accuracy plot shown using matplotlib
