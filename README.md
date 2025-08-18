# Dive into Deep Learning – Exercises Solutions

This repository contains my solutions and implementations of the exercises from the book **[Dive into Deep Learning (D2L)](https://d2l.ai/)**.  
The aim is to build a strong foundation in deep learning by coding every exercise from scratch.

---

## 📚 About the Book
**Dive into Deep Learning (D2L)** is an open-source, interactive book that teaches deep learning through both **theory** and **practical coding**.  
It covers:
- Mathematics (linear algebra, probability, optimization)
- Core machine learning concepts
- Deep neural networks (MLPs, CNNs, RNNs, Attention, Transformers)
- Real-world applications (NLP, Computer Vision, RL)
- Performance and deployment

---

## 🗂 Repository Structure
This repo is organized chapter by chapter:

```
├── Chapter01_Introduction/
├── Chapter02_Preliminaries/
├── Chapter03_Linear_Neural_Networks/
├── Chapter04_Multilayer_Perceptrons/
├── Chapter05_Deep_Learning_Computation/
├── Chapter06_CNN/
├── Chapter07_Modern_CNN/
├── Chapter08_Recurrent_Neural_Networks/
├── Chapter09_Attention/
├── Chapter10_Optimization/
├── Chapter11_Computational_Performance/
├── Chapter12_Computer_Vision/
├── Chapter13_NLP/
└── Chapter14_Reinforcement_Learning/
```

Each folder contains:
- **notebooks/** → Jupyter notebooks with solutions  
- **code/** → Python scripts for reusable implementations  
- **README.md** → Quick notes for that chapter  

---

## ⚙️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/d2l-exercises.git
   cd d2l-exercises
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv d2l-env
   source d2l-env/bin/activate   # Linux/Mac
   d2l-env\Scripts\activate      # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🛠 Requirements
- Python 3.8+  
- Jupyter Notebook / JupyterLab  
- PyTorch (or MXNet/TensorFlow depending on your chosen backend)  
- Matplotlib, NumPy, pandas  
- `d2l` package (`pip install d2l`)  
