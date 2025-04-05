# 💳 Synthetic Fraud Detection Dataset using GANs

This project leverages **Generative Adversarial Networks (GANs)** to generate a synthetic dataset that closely replicates the structure and patterns of a real-world credit card transaction dataset. The synthetic data is used to train a machine learning model for **fraud detection**, enabling privacy-safe and scalable experimentation.

---

## 🚀 Project Overview

- **Objective**: Create a high-fidelity synthetic dataset for fraud detection using GANs.
- **Tools & Frameworks**: Python, Pandas, Scikit-learn, TensorFlow/Keras, GANs
- **Use Case**: Classification of fraudulent vs. legitimate credit card transactions

---

## 🧰 Libraries & Technologies Used

| Category          | Libraries/Technologies                        |
|-------------------|-----------------------------------------------|
| Programming       | Python 3.x                                    |
| Data Handling     | pandas, numpy                                 |
| Visualization     | matplotlib, seaborn                           |
| Machine Learning  | scikit-learn                                  |
| Deep Learning     | TensorFlow, Keras                             |
| GAN Architecture  | Custom Generator & Discriminator (Keras-based)|
| Model Evaluation  | accuracy_score from sklearn.metrics           |

---

## 📊 Model Performance Comparison

| Dataset Type      | Accuracy |
|-------------------|----------|
| Real Dataset      | 96.8%    |
| Synthetic Dataset | 97.1%    |

> ✅ *The synthetic dataset closely mirrors the original dataset, achieving comparable model performance, which confirms the GAN’s effectiveness in capturing real-world data distribution.*

---

## 🔐 Use Case & Significance

This project demonstrates how **synthetic datasets** can be used to:

- Replace or supplement sensitive real-world data in training pipelines
- Avoid **data privacy breaches**
- Enable safe **data sharing and collaboration** across organizations
- Facilitate **model development in regulated industries** (like finance and healthcare) without risking exposure of confidential information

---

## 📁 Files Included

- `SyntheticDataset.ipynb`: Jupyter notebook with the full pipeline
- `credit_card_data.csv`: Original dataset (input)
- `synthetic_credit_card_data.csv`: GAN-generated synthetic dataset (output)
- `README.md`: Project documentation

---

