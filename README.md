# Loss Functions (Deep Learning Basics)

This project demonstrates the **manual implementation of common loss functions** used in Deep Learning.

Instead of using built-in libraries like TensorFlow or Keras, all loss functions are implemented **from scratch using Python and NumPy** for better conceptual understanding.

---

## Objective

- Understand how loss functions work internally
- Implement core loss functions manually
- Compare predicted values with actual values
- Build strong fundamentals for Deep Learning interviews

---

##  Loss Functions Implemented

### 1. Mean Squared Error (MSE)
- Used for regression problems
- Measures average squared difference between actual and predicted values

**Formula:**
MSE = (1/n) * Σ(y_true - y_pred)^2

---

### 2. Mean Absolute Error (MAE)
- Used for regression
- Measures absolute difference

**Formula:**
MAE = (1/n) * Σ|y_true - y_pred|

---

### 3. Binary Cross Entropy (Log Loss)
- Used for binary classification (0 or 1)
- Works with probabilities (sigmoid output)

**Formula:**
Loss = -[y log(p) + (1 - y) log(1 - p)]

---

### 4. Categorical Cross Entropy
- Used for multi-class classification
- Works with one-hot encoded labels

**Formula:**
Loss = -Σ(y_true * log(y_pred))

---

### 5. Sparse Categorical Cross Entropy
- Used when labels are integers instead of one-hot encoding

**Formula:**
Loss = -log(p_correct_class)

---

## Technologies Used

- Python
- NumPy

---

##  Why This Project?

In real-world Deep Learning:
- Libraries automatically compute loss
- But understanding **how loss is calculated** is important

This project helps to:
- Learn mathematical intuition
- Understand model optimization

---

##  Key Learnings

- Difference between regression and classification loss functions
- Importance of loss in model training
- How prediction errors are calculated
- Why cross entropy is preferred over MSE for classification

---

## Future Improvements

- Add visualization (loss vs epochs)
- Implement gradient descent manually
- Compare with TensorFlow/Keras outputs

---
