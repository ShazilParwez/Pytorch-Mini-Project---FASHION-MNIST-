# Pytorch-Mini-Project---FASHION-MNIST
# 👕 Fashion MNIST Classification (Mini DL Project with PyTorch)

## 📌 Problem Statement
The goal of this project is to **classify images of clothing items** (e.g., shirts, shoes, bags) using the **Fashion MNIST dataset**.  
This is a benchmark dataset for testing **deep learning models on image classification tasks**.

---

## 📊 Dataset
- **Source:** [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)  
- **Training samples:** 60,000 grayscale images  
- **Test samples:** 10,000 grayscale images  
- Each image: **28x28 pixels**  
- Target classes: 10 types of clothing (T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)  

---

## 🔎 Workflow
1. **Data Loading** – Loaded Fashion MNIST dataset using PyTorch’s `torchvision.datasets`.  
2. **Exploratory Analysis** – Visualized sample images and class distribution.  
3. **Preprocessing** –  
   - Normalized pixel values (0–1)  
   - Converted images to PyTorch tensors  
4. **Model Building** –  
   - Built a **simple feedforward neural network** in PyTorch  
   - Layers: Input → Hidden → Output (Softmax)  
5. **Training** –  
   - Used **CrossEntropyLoss** and **Adam optimizer**  
   - Trained the model on training data for multiple epochs  
6. **Evaluation** – Tested the model on the test set and measured accuracy  

---

## 📈 Results
- **Accuracy:** ~88–90% on test data  
- Model successfully classifies clothing items from Fashion MNIST.  

---

## 🛠 Tech Stack
- Python  
- PyTorch / Torchvision  
- NumPy, Matplotlib (for visualization)  

---
