### Predicting Exam Scores Using a Neural Network

---

### **Table of Contents**
1. [Overview](#overview)
2. [Model Architecture](#model-architecture)
3. [Hyperparameter Tuning](#hyperparameter-tuning)
4. [Results](#results)
5. [Future Improvements](#future-improvements)
6. [Collaboration](#collaboration)
7. [Authors](#authors)

---

### **1. Overview**

This project builds and trains a neural network to predict student exam scores based on available dataset features. The model is optimized through hyperparameter tuning to achieve better accuracy and stability.

### **2. Model Architecture**

Three hidden layers: 64, 32, and 16 neurons, respectively.

Activation function: LeakyReLU (prevents dying neurons and allows learning for negative outputs).

Optimizer: Adam (adaptive learning rate optimization for efficient convergence).

Loss Function: Mean Squared Error (MSE) to measure prediction accuracy.

### **3. Hyperparameter Tuning**

Different learning rates tested: 0.1, 0.01, 0.001.

Different epochs tested: 100, 500, 1000.

Found that lower learning rates resulted in better convergence and higher stability in loss function behavior.

### **4. Results**

The final model achieves stable loss convergence.

Tuning hyperparameters helped reduce fluctuations in the learning process.

Predictions closely align with actual exam scores.

### **5. Future Improvements**

Experiment with different architectures (e.g., additional layers or neurons).

Implement dropout to prevent overfitting.

Try alternative activation functions and optimizers.

### **6. Collaboration**

This project was completed in collaboration with Karen Bou Daou during the 'Introduction to AI and Deep Learning' class.

### **7. Authors**

Juliana Hubacova & Karen Bou Daou
