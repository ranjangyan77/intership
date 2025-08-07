
# 📊 Telecom Customer Churn Prediction

This project aims to predict customer churn in a telecom company using a neural network model. The model is trained on a cleaned and preprocessed dataset and evaluated using classification metrics.

---

## 🚀 Features

- Data cleaning and preprocessing
- One-hot encoding of categorical features
- Neural network built using Keras (Sequential API)
- Evaluation using confusion matrix and classification report
- Accuracy plots for training and validation

---

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Keras (TensorFlow backend)

---

## 📁 Dataset

The dataset is sourced from [YBI Foundation GitHub](https://github.com/YBIFoundation/Dataset) and loaded via:

```python
url = 'https://raw.githubusercontent.com/YBIFoundation/Dataset/refs/heads/main/TelecomCustomerChurn.csv'
```

---

## ⚙️ How It Works

1. Load the dataset and preprocess it:
   - Drop `customerID`
   - Handle missing values
   - Convert categorical variables to dummy variables

2. Split the dataset into train and test sets.

3. Normalize the data using `StandardScaler`.

4. Define a neural network with:
   - Input layer matching feature size
   - Two hidden layers (32 and 16 neurons)
   - Output layer with sigmoid activation for binary classification

5. Train the model and evaluate on test data.

6. Visualize training and validation accuracy over epochs.

---

## 📈 Model Performance

- Accuracy printed after model evaluation
- Confusion matrix and classification report displayed
- Accuracy plot shown using matplotlib

---

## 🔧 Installation

To run this project locally:

```bash
pip install pandas numpy matplotlib scikit-learn keras
```

---

## ▶️ Run the Script

```bash
python intership.py
```

---

## 📬 Contact

For questions or feedback, feel free to open an issue or reach out.
