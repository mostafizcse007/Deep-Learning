# 🧠 Deep Learning

A structured collection of Jupyter Notebooks covering fundamental and intermediate Deep Learning concepts, built using **TensorFlow/Keras** and **PyTorch**.

## 📁 Repository Structure

```
Deep-Learning/
├── Week 1/
│   ├── Perceptron.ipynb
│   ├── Perceptron_problems.ipynb
│   ├── Perceptron_gradient_descent.ipynb
│   ├── Customer_prediction.ipynb
│   ├── Admission_prediction.ipynb
│   ├── Handwritten_digit_classification.ipynb
│   └── Admission_Predict.csv
└── Week 2/
    ├── Basics_of_tensor.ipynb
    ├── Tensors.ipynb
    ├── Autograd.ipynb
    ├── NN_module.ipynb
    ├── Dataset_dataloader.ipynb
    ├── Backpropagation_scratch_regression.ipynb
    └── Training_Pipeline.ipynb
```

---

## 📚 Week 1 — Foundations with TensorFlow/Keras

| Notebook | Description |
|---|---|
| `Perceptron.ipynb` | Introduction to the Perceptron algorithm using `sklearn`. Trains on a student placement dataset (CGPA & resume score). |
| `Perceptron_problems.ipynb` | Applies Perceptron to classic logic gate problems: AND, OR, and XOR. Visualizes decision boundaries. |
| `Perceptron_gradient_descent.ipynb` | Implements a Perceptron from scratch using gradient descent on a synthetically generated dataset. |
| `Customer_prediction.ipynb` | Binary classification using a Keras `Sequential` model to predict customer churn from the Churn Modelling dataset. |
| `Admission_prediction.ipynb` | Regression task predicting the chance of graduate admission using a Keras neural network. |
| `Handwritten_digit_classification.ipynb` | Classifies handwritten digits from the MNIST dataset using a fully connected Keras neural network. |

---

## 📚 Week 2 — PyTorch Fundamentals & Training Pipelines

| Notebook | Description |
|---|---|
| `Basics_of_tensor.ipynb` | Covers fundamental PyTorch tensor operations: creation, types, shapes, and basic math. |
| `Tensors.ipynb` | Deeper exploration of PyTorch tensors including indexing, slicing, and tensor manipulations. |
| `Autograd.ipynb` | Demonstrates PyTorch's automatic differentiation engine (`autograd`) for computing gradients. |
| `NN_module.ipynb` | Builds a neural network using `torch.nn.Module` with `Sequential` layers, ReLU, and Sigmoid activations. |
| `Dataset_dataloader.ipynb` | Implements a custom `Dataset` class and uses `DataLoader` for efficient batching and shuffling. |
| `Backpropagation_scratch_regression.ipynb` | Implements backpropagation from scratch for a regression problem without using high-level libraries. |
| `Training_Pipeline.ipynb` | End-to-end PyTorch training pipeline for binary classification on the Breast Cancer dataset, including data loading, model definition, training loop, and evaluation. |

---

## 🛠️ Technologies & Libraries

- **Python 3**
- **TensorFlow / Keras** — Week 1 models
- **PyTorch** — Week 2 models
- **NumPy** — Numerical computing
- **Pandas** — Data manipulation
- **Matplotlib / Seaborn** — Data visualization
- **Scikit-learn** — Preprocessing, metrics, and utilities
- **mlxtend** — Decision region plotting

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/mostafizcse007/Deep-Learning.git
   cd Deep-Learning
   ```

2. **Install dependencies**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow torch torchinfo mlxtend
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. Navigate to the desired week's folder and open any `.ipynb` file to get started.

---

## 📌 Topics Covered

- ✅ Perceptron & gradient descent
- ✅ Logic gate classification (AND, OR, XOR)
- ✅ Binary & multi-class classification
- ✅ Regression with neural networks
- ✅ MNIST digit recognition
- ✅ PyTorch tensor fundamentals
- ✅ Automatic differentiation (Autograd)
- ✅ Custom Dataset & DataLoader
- ✅ Building models with `nn.Module`
- ✅ Full training pipelines in PyTorch
- ✅ Backpropagation from scratch

---

## 👤 Author

**Mostafiz** — [@mostafizcse007](https://github.com/mostafizcse007)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).