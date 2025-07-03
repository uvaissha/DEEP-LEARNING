# Handwritten Digit Classification using TensorFlow

This project demonstrates how to build and train a simple neural network using **TensorFlow** and **Python** to classify handwritten digits from the MNIST dataset. We'll begin with a basic neural network containing only input and output layers, and later enhance it by adding a hidden layer. The performance improvement will be visualized using a **Seaborn-plotted confusion matrix**.

---

## 🚀 What You'll Learn

- Loading and preprocessing the MNIST dataset
- Building a simple neural network using TensorFlow/Keras
- Adding hidden layers to improve performance
- Training and evaluating the model
- Visualizing accuracy using a confusion matrix with Seaborn

---

## 🧠 Model Architectures

### 1. **Simple Model**
- **Input Layer**: 784 neurons (28x28 pixels)
- **Output Layer**: 10 neurons (digit classes 0–9)
- **Activation**: Softmax

### 2. **Model with Hidden Layer**
- **Input Layer**: 784 neurons
- **Hidden Layer**: 100 neurons (ReLU)
- **Output Layer**: 10 neurons (Softmax)

---

## 📊 Confusion Matrix

We evaluate the model's predictions using a **confusion matrix**, which is plotted using **Seaborn** for better visualization and interpretation of accuracy.

---

## 🛠️ Technologies Used

- Python 🐍
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn

---

## 🧪 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/handwritten-digit-classifier.git
cd handwritten-digit-classifier
