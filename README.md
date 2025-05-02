# 🛡️ Autoencoder-Based Adversarial Detection and Defense

This repository provides an implementation of an **autoencoder-based defense mechanism** to detect and mitigate adversarial attacks on machine learning models. The approach includes:

- Training a **denoising autoencoder** to learn the reconstruction of clean input data.
- Identifying adversarial samples using reconstruction error (MSE).
- Filtering or flagging adversarial inputs before classification.
- Enhancing robustness through **adversarial training** using a `RandomForestClassifier`.

---

## 📌 Features

- 🔍 Adversarial detection using autoencoder reconstruction error.
- 📈 Visual diagnostics: MSE distribution and confusion matrices.
- 🧪 Adversarial training for improved model robustness.
- 💡 Compatible with scikit-learn and TensorFlow workflows.

---
## 📊 Visualizations
📌 Confusion Matrix of adversarial detection

📈 MSE Plot per sample with detection threshold

🔎 Annotated top anomaly scores

All plots are generated using matplotlib and seaborn.


