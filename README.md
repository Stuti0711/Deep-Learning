# Deep-Learning

This repository is a collection of hands-on deep learning projects, each exploring a different aspect of neural networks using Python and Google Colab. The goal is to apply deep learning techniques in practical scenarios like image preprocessing, regression tasks, and time series forecasting.

---

## 📁 Project Descriptions

### 1. 📸 Image Preprocessing - `Image_preprocessing.ipynb`

This notebook focuses on preparing image data for training deep learning models. It includes:

- **Image Loading & Resizing**: Loading datasets and resizing images to ensure consistent input shape for neural networks.
- **Normalization**: Scaling pixel values for faster convergence.
- **Data Augmentation**: Applying transformations like rotation, flipping, and zooming to artificially expand the dataset and improve model generalization.
- **Use Case**: Ideal for CNN model pipelines where data quality and consistency are critical.

> **Outcome**: A clean and augmented image dataset, ready for training convolutional neural networks.

---

### 2. 🔢 Regression Using Keras - `Regression_Keras.ipynb`

This notebook demonstrates how to solve a regression problem using a feedforward neural network built with **Keras**:

- **Dataset Preparation**: Loading and preprocessing tabular data.
- **Model Architecture**: Defining a multi-layer perceptron (MLP) model suitable for predicting continuous values.
- **Training & Evaluation**: Compiling the model with appropriate loss functions (like MSE) and using training/validation splits.
- **Visualization**: Plotting training history (loss/metrics) to understand model performance over time.

> **Outcome**: A trained model capable of accurately predicting continuous outputs, useful for tasks like price prediction, demand forecasting, etc.

---

### 3. ⏳ Time Series Forecasting - `TimeSeries.ipynb`

This project explores deep learning methods for forecasting future values in a time-dependent dataset:

- **Time Series Visualization**: Plotting historical data to understand trends and seasonality.
- **Data Framing**: Transforming time series into supervised learning format (sliding window approach).
- **LSTM Implementation**: Building a Long Short-Term Memory (LSTM) network to learn temporal dependencies.
- **Forecasting & Evaluation**: Generating future predictions and comparing them to actual data.

> **Outcome**: A deep learning-based model that can predict future values from sequential time series data, suitable for applications like stock prediction or weather forecasting.

---

## 🚀 Technologies Used

- Python 3.x
- Google Colab
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Stuti0711/Deep-Learning.git
