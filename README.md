# Micrograd - Manual Backpropagation 🧮

A minimal **autograd engine** built from scratch in Python, inspired by [Karpathy’s micrograd](https://github.com/karpathy/micrograd).  
This project demonstrates how **backpropagation** works under the hood without relying on deep learning frameworks.

---

## 🚀 Features
- Tiny **computational graph** for scalar values  
- **Forward pass** for mathematical operations  
- **Backward pass** with manual backpropagation  
- Implemented in **pure Python** (no TensorFlow/PyTorch)  
- Designed and tested in **Google Colab**  

---

## 🔧 Tech Stack
- Python 3.x  
- Jupyter / Google Colab  
- NumPy (optional for experiments)  

---

## 📂 Repository Structure
micrograd-project/
│── Micrograd.ipynb # Colab notebook with implementation + experiments
│── README.md # Project documentation
│── requirements.txt # Dependencies (optional)

yaml
Copy
Edit

---

## 📘 How It Works
- Define scalar values as **nodes** in a computation graph.  
- Perform operations (add, multiply, etc.) while building the graph.  
- Run **forward propagation** to compute results.  
- Call `.backward()` to apply **chain rule of differentiation** and compute gradients.  

---

## ▶️ Run the Project

### 🔗 Run in Google Colab
Click below to open the notebook directly in Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YourUsername/micrograd-project/blob/main/Micrograd.ipynb)

*(Replace `YourUsername` with your GitHub username)*

### 💻 Run Locally
```bash
git clone https://github.com/YourUsername/micrograd-project.git
cd micrograd-project
pip install -r requirements.txt
jupyter notebook Micrograd.ipynb
📖 References
Micrograd by Andrej Karpathy

👩‍💻 Author
Spandana Ray

yaml
Copy
Edit
