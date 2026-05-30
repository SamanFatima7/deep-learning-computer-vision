# Deep Learning — Computer Vision

> CNN classifiers built and tuned for real image datasets. Heavy emphasis on agricultural disease detection — because food security is a real problem and image models are part of the answer.

This repo collects deep-learning notebooks focused on image classification. Most of them land in the 90–98% accuracy range on their respective test sets, and each one walks through the full pipeline — data inspection, augmentation, architecture choice, training, evaluation, and where the model still makes mistakes.

---

## 📓 Notebooks in this repo

### 1. Tomato Leaf Disease Classifier — 94% Accuracy 🍃🍅
A multi-class CNN that distinguishes healthy tomato leaves from nine different disease categories. Includes data augmentation strategy, transfer-learning comparisons, and a clean confusion matrix so you can see *which* diseases the model still confuses.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/tomato-leaf-disease-94-accuracy)** · ⭐ 1947 votes

---

### 2. Cat 🐱 vs Dog 🐶 Classifier — 98% Accuracy
The classic vision benchmark, done right. Transfer learning, proper validation strategy, and a discussion of where the remaining 2% error comes from (spoiler: it's mostly the photos *humans* would also get wrong).

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/cat-and-dog-classifier-98-accuracy)**

---

### 3. Rice Disease Classification — Step by Step 🌾
A teaching-grade walkthrough on a rice-leaf disease dataset. Built so you can follow every decision: why this preprocessing, why this architecture, why this loss. Useful as a template for any plant-disease classification project.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/rice-disease-classification-step-by-step)**

---

### 4. Grapevine Leaf Ninja 🍇 — 90% Accuracy
A multi-class classifier for grapevine leaf varieties. The dataset is smaller than the others, so this notebook gets into the details of avoiding overfitting on a tight budget — early stopping, dropout, and learning-rate scheduling.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/grapevine-leaf-ninja-90-accuracy)**

---

### 5. Orange Disease Prediction — 95% Accuracy 🍊
A CNN trained to identify citrus diseases from leaf images. The notebook double-checks that high accuracy isn't a class-imbalance artifact — a small detail that catches a lot of public CV notebooks off-guard.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/crushing-95-accuracy-orange-disease-prediction)**

---

## 🛠 Stack

Python · TensorFlow / Keras · OpenCV · NumPy · Matplotlib · Pillow

## 📂 How this repo is organized

Each notebook lives in its own `.ipynb`. Datasets are public on Kaggle and linked inside each notebook. To run locally:

```bash
git clone https://github.com/samanfatima7/deep-learning-computer-vision.git
cd deep-learning-computer-vision
pip install -r requirements.txt
jupyter notebook
```

A GPU is recommended for training but not required — every notebook is also runnable in a Kaggle Kernel for free.

## 🧭 Why so much plant-disease work?

Most of these datasets come from agricultural research labs in countries where smallholder farmers don't have easy access to plant pathologists. A phone-camera classifier that runs offline can be the difference between catching a disease early and losing a season's harvest. It's a small contribution, but it's a real one.

## 👋 About

Saman Fatima — Kaggle Legacy Grandmaster, data scientist from Pakistan. Find more of my work on [Kaggle](https://www.kaggle.com/samanfatima7) and [LinkedIn](https://www.linkedin.com/in/saman-fatima-datascience/).

⭐ if any of these helped — and reach out if you're working on something in this space, I love collaborating.
# Deep Learning — Computer Vision

> CNN classifiers built and tuned for real image datasets. Heavy emphasis on agricultural disease detection — because food security is a real problem and image models are part of the answer.

This repo collects deep-learning notebooks focused on image classification. Most of them land in the 90–98% accuracy range on their respective test sets, and each one walks through the full pipeline — data inspection, augmentation, architecture choice, training, evaluation, and where the model still makes mistakes.

---

## 📓 Notebooks in this repo

### 1. Tomato Leaf Disease Classifier — 94% Accuracy 🍃🍅
A multi-class CNN that distinguishes healthy tomato leaves from nine different disease categories. Includes data augmentation strategy, transfer-learning comparisons, and a clean confusion matrix so you can see *which* diseases the model still confuses.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/tomato-leaf-disease-94-accuracy)** · ⭐ 1947 votes

---

### 2. Cat 🐱 vs Dog 🐶 Classifier — 98% Accuracy
The classic vision benchmark, done right. Transfer learning, proper validation strategy, and a discussion of where the remaining 2% error comes from (spoiler: it's mostly the photos *humans* would also get wrong).

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/cat-and-dog-classifier-98-accuracy)**

---

### 3. Rice Disease Classification — Step by Step 🌾
A teaching-grade walkthrough on a rice-leaf disease dataset. Built so you can follow every decision: why this preprocessing, why this architecture, why this loss. Useful as a template for any plant-disease classification project.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/rice-disease-classification-step-by-step)**

---

### 4. Grapevine Leaf Ninja 🍇 — 90% Accuracy
A multi-class classifier for grapevine leaf varieties. The dataset is smaller than the others, so this notebook gets into the details of avoiding overfitting on a tight budget — early stopping, dropout, and learning-rate scheduling.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/grapevine-leaf-ninja-90-accuracy)**

---

### 5. Orange Disease Prediction — 95% Accuracy 🍊
A CNN trained to identify citrus diseases from leaf images. The notebook double-checks that high accuracy isn't a class-imbalance artifact — a small detail that catches a lot of public CV notebooks off-guard.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/crushing-95-accuracy-orange-disease-prediction)**

---

## 🛠 Stack

Python · TensorFlow / Keras · OpenCV · NumPy · Matplotlib · Pillow

## 📂 How this repo is organized

Each notebook lives in its own `.ipynb`. Datasets are public on Kaggle and linked inside each notebook. To run locally:

```bash
git clone https://github.com/samanfatima7/deep-learning-computer-vision.git
cd deep-learning-computer-vision
pip install -r requirements.txt
jupyter notebook
```

A GPU is recommended for training but not required — every notebook is also runnable in a Kaggle Kernel for free.

## 🧭 Why so much plant-disease work?

Most of these datasets come from agricultural research labs in countries where smallholder farmers don't have easy access to plant pathologists. A phone-camera classifier that runs offline can be the difference between catching a disease early and losing a season's harvest. It's a small contribution, but it's a real one.

## 👋 About

Saman Fatima — Kaggle Grandmaster, data scientist from Pakistan. Find more of my work on [Kaggle](https://www.kaggle.com/samanfatima7) and [LinkedIn](https://www.linkedin.com/in/saman-fatima-datascience/).

⭐ if any of these helped — and reach out if you're working on something in this space, I love collaborating.
