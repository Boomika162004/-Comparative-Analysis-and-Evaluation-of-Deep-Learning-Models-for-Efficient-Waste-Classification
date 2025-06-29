This repository hosts the source code, datasets, results, and methodology behind the research paper presented at the **IEEE 5th International Conference on Intelligent Technologies (CONIT 2025)**.

> **Title**: Comparative Analysis and Evaluation of Deep Learning Models for Efficient Waste Classification  
> **Authors**: Boomika B, D N Padmashri, Arushi G Hiregoudar, Moni Shree S  
> **Conference**: IEEE CONIT 2025  
> **Focus**: Deep Learning · CNNs · Waste Classification · Sustainability

---

## 🧠 Summary
- 📌 Compared 5 CNN architectures:
  - VGG19  
  - InceptionV3  
  - DenseNet121 *(Best performing model)*  
  - ResNet50  
  - EfficientNetB0
  - 
- 🗂️ Trained across 3 distinct datasets (Kaggle + GitHub)

- 🧪 Techniques used:
  - Data Augmentation
  - Class Balancing
  - Transfer Learning + Fine-Tuning
  - Evaluation Metrics: Accuracy, Precision, Recall, F1-score

- 🏆 DenseNet121 achieved:
  - **Training Accuracy**: 99.80%
  - **Validation Accuracy**: 87.36%
  - **F1-score**: 1.00 on Dataset 2

---

## 🖼️ Outputs

- Model comparison charts (accuracy, loss, precision, F1-score)
- Dataset-wise evaluation
- Training time observations
- Model architecture effect on classification robustness

---

## 📂 Folder Structure

waste-classification/
│
├── data/ # Raw and preprocessed datasets


├── models/ # Trained models (.h5 files)

├── src/ # Scripts for training, testing, evaluation

├── notebooks/ # Jupyter notebooks for experimentation
├── results/ # Evaluation metrics, plots
├── figures/ # Graphs used in the paper
├── paper/ # Ecobin.pdf and citation
└── README.md # This file


🌱 Social Impact
🧹 Automates waste segregation using smart deep learning-based systems

♻️ Promotes efficient recycling and circular economy

💼 Supports rag-picker communities with safer, automated classification

🏙️ Enables smart cities through IoT-integrated smart bins

🔭 Future Scope

Mobile app for real-time trash detection

Integration into smart bins using edge AI

Larger, diverse datasets for better generalization

Hardware optimization for embedded deployment

Semi-supervised learning to reduce data labeling effort

Federated learning for decentralized and privacy-friendly training


