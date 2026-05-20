# 🦋 Butterfly Species Classification using CNN

A deep learning project for classifying butterfly species from images using Convolutional Neural Networks (CNN), built with **PyTorch**. Includes full data preprocessing pipeline, training of two custom CNN architectures, and evaluation of different activation functions.

---

## 📊 Project Overview

This project explores image classification through the lens of butterfly species recognition. Two CNN architectures — **SimpleCNN** and **DeepCNN** — were designed, trained, and compared to analyze the impact of network depth and activation functions on classification accuracy.

---

## ✨ What's Inside

- 🧹 **Data Preprocessing**
  - Duplicate image removal
  - Image resizing & normalization
  - Data augmentation (flips, rotations, color jitter)

- 🏗️ **Model Architectures**
  - `SimpleCNN` — lightweight baseline model
  - `DeepCNN` — deeper architecture for improved feature extraction

- ⚡ **Activation Function Comparison**
  - ReLU, LeakyReLU, and others evaluated side-by-side

- 📈 **Visualization**
  - Training & validation loss/accuracy curves
  - Confusion matrix
  - Sample predictions with confidence scores

---

## 🛠️ Tech Stack

| Category        | Library                          |
|-----------------|----------------------------------|
| Deep Learning   | PyTorch, torchvision             |
| Data Processing | Pandas, NumPy, Pillow            |
| Visualization   | Matplotlib, Seaborn              |
| Evaluation      | Scikit-learn                     |
| Environment     | Google Colab                     |

---

## 🧠 Model Architecture

### SimpleCNN
```
Input → Conv2d → ReLU → MaxPool
      → Conv2d → ReLU → MaxPool
      → Flatten → Linear → Output
```

### DeepCNN
```
Input → Conv2d → BN → ReLU → MaxPool
      → Conv2d → BN → ReLU → MaxPool
      → Conv2d → BN → ReLU → MaxPool
      → Flatten → Linear → Dropout → Linear → Output
```

---

## 🚀 Getting Started

### Run Locally
```bash
# 1. Clone the repository
git clone https://github.com/Hirad1380/butterfly-cnn-classifier.git
cd butterfly-cnn-classifier

# 2. Install dependencies
pip install torch torchvision pandas numpy pillow matplotlib seaborn scikit-learn

# 3. Open the notebook
jupyter notebook Butterfly.ipynb
```

---

## 📁 Project Structure

```
butterfly-cnn-classifier/
│
├── Butterfly.ipynb        # Main notebook — preprocessing, training, evaluation
└── README.md
```

---

## 👨‍💻 Author

**Hirad Bayat**  
M.Sc. Applied Computer Science — University of Duisburg-Essen  
📧 Bayathirad7@gmail.com  
🔗 LinkedIn: [Hirad Bayat](https://www.linkedin.com/in/hirad-bayat-911480383)  
🐙 GitHub: [Hirad1380](https://github.com/Hirad1380)
