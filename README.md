# Neural Network From Scratch vs Keras on MNIST

## 📌 Overview

This project compares a **Neural Network From Scratch (NNFS)** implemented using NumPy with a **TensorFlow/Keras** implementation on the MNIST handwritten digit dataset.

The project demonstrates:

* Forward & backward propagation
* ReLU and Softmax activations
* Categorical Cross-Entropy loss
* Adam optimizer
* Accuracy and loss comparison between custom and framework-based models

---

## 🚀 Technologies Used

* Python
* NumPy
* TensorFlow/Keras
* Matplotlib
* Jupyter Notebook

---

## 🧠 Model Architecture

```text id="olhq33"
Input (784)
   ↓
Dense Layer
   ↓
ReLU
   ↓
Dense Layer
   ↓
Softmax
```

---

## 📊 Results

| Model                       | Accuracy |
| --------------------------- | -------- |
| Neural Network From Scratch | ~98.1%   |
| TensorFlow/Keras            | ~99–100%  |

---

## 📈 Features

* Manual neural network implementation
* Backpropagation from scratch
* Keras-based implementation
* Accuracy & loss visualization
* MNIST training and evaluation

---

## ▶️ Run Project

Install dependencies:

```bash id="jlwmwp"
pip install numpy matplotlib tensorflow
```

Run notebook:

```bash id="pdd0o7"
jupyter notebook
```

---

## 📌 Conclusion

The NumPy-based neural network achieved performance comparable to TensorFlow/Keras while providing deeper understanding of neural network internals and optimization mechanics.

---

## 👨‍💻 Author

Sudhir
Ph.D. Scholar, Indian Institute of Technology Kharagpur
