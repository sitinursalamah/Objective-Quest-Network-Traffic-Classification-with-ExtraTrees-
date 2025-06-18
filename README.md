# Multiclass Network Traffic Classification for Cyber Threat Detection
🏆 Kaggle Competition | Dataquest 2024 
📊 Final Rank: **43rd out of 88 teams**

This project was developed for the **Objective Quest** competition held during **Dataquest 2024**, focusing on building a reliable and reproducible machine learning pipeline to classify **network traffic behavior** for cybersecurity applications.

---

## 🎯 Objective

To classify network traffic into six categories—ranging from benign to suspicious and malicious—based on historical data. The model aims to detect early threats in network activity and support cybersecurity monitoring in high-traffic systems.

---

## 📦 Dataset & Classes

- **Provided Files**: `train.csv`, `test.csv`
- **Target Column**: `traffic`
- **Classes**:
  - `Background`  
  - `Benign`  
  - `Probing`  
  - `Bruteforce`  
  - `XMRIGCC CryptoMiner`  
  - `Bruteforce-XML`

---

## ⚙️ Model Overview

### ✅ Model Used: **ExtraTreesClassifier**  
An ensemble tree-based model that works well on tabular classification tasks.
