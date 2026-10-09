<div align="center">

# 🚫 Toxic Comment Classification

**A deep-learning NLP model that flags toxic online comments - with a Gradio demo.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316)
![Colab](https://img.shields.io/badge/Open_in-Colab-F9AB00?logo=googlecolab&logoColor=white)

</div>

---

## ✨ Overview

The notebook builds a multi-label classifier that identifies toxic comments (the Jigsaw *Toxic Comment Classification* data: `train.csv`, `test.csv`, `test_labels.csv`) using Keras text vectorization and a neural network, trained on the training set only.

- 🎯 Validation accuracy of about **99 %** in the recorded training run (5 epochs).
- 🖥️ A **Gradio** interface lets you type a comment and see the toxicity predictions.
- ☁️ Designed to run in Google Colab:
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Arashomranpour/toxic_comment/blob/main/toxic_comment_classification.ipynb)

## 📸 Screenshots

Model accuracy

![Model accuracy](https://github.com/user-attachments/assets/2bbe3a5f-ab4c-473e-97b2-b59d018c7a28)

Metrics with plots

![Metrics](https://github.com/user-attachments/assets/ba9a972b-d8f9-4dae-9cb7-fa589e2daa61)
![Metrics](https://github.com/user-attachments/assets/b43e48cf-3c43-48b3-9c23-1b9640417477)

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/toxic_comment.git
cd toxic_comment
pip install tensorflow keras pandas numpy matplotlib gradio jupyter
jupyter notebook toxic_comment_classification.ipynb
```

Download the Jigsaw dataset from Kaggle and place `train.csv`, `test.csv` and `test_labels.csv` next to the notebook (or upload them in Colab).

## 📁 Project Structure

```
.
└── toxic_comment_classification.ipynb
```

## 🛠️ Tech Stack

`TensorFlow / Keras` · `pandas` · `NumPy` · `Gradio`
