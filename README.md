# project_hand_guesture
this project detects the basic hand guestures for the alphabets using data that has been used to train the model

## 📄 Overview
The project was built using **Google Colab** and implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the **MNIST dataset**. The model was built using **PyTorch** and achieved an accuracy of **93.81%** on the test data.

## 💾 Dataset
The model utilizes the **MNIST** dataset in CSV format, sourced from Kaggle.
* **Source:** https://www.kaggle.com/datasets/datamunge/sign-language-mnist?resource=download
* **Files used:**
    * `mnist_train.csv` (Training data)
    * `mnist_test.csv` (Testing data)

## 🛠️ Tech Stack
* **Environment:** Google Colab (Jupyter Notebook)
* **Deep Learning Framework:** PyTorch
* **Data Manipulation:** Pandas, NumPy
* **Language:** Python

## 🚀 Key Concepts Applied
* **CNN Architecture:** Implementation of Convolutional layers, Pooling layers, and Fully Connected layers.
* **Data Loading:** Using Pandas to parse CSV data into PyTorch tensors.
* **Evaluation:** Measuring model performance on unseen test data.

## 📊 Model Performance
* **Accuracy:** 93.81%

## 💻 How to Run
1.  **Open the Notebook:**
    Click the "Open in Colab" badge above, or view the `.ipynb` file in this repository.

2.  **Get the Data:**
    * Download `mnist_train.csv` and `mnist_test.csv` from Kaggle.

3.  **Upload Data to Colab:**
    * Upload Train and Test csv files in the second and third cells respectively

4.  **Run:**
    * Execute the cells in order to train the model and see the predictions.
