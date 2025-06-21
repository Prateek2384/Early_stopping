# EarlyStopping Demo in Keras

This repository contains a sample Jupyter Notebook that demonstrates how to use the `EarlyStopping` callback in Keras to prevent overfitting during model training.

## 🔍 What is EarlyStopping?

EarlyStopping is a regularization technique used in deep learning to **stop training when the model's performance stops improving on a validation set**. It helps:
- Reduce overfitting
- Save training time
- Improve generalization

## 📁 Files

- `earlystopping_demo.ipynb` – Jupyter Notebook demonstrating how to use EarlyStopping with a sample neural network.

## 📌 Key Features Demonstrated

- Use of `EarlyStopping` from `tensorflow.keras.callbacks`
- Monitoring `val_loss` to stop training early
- Restoring the best model weights using `restore_best_weights=True`
- Visualizing training vs. validation loss

