<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=2500&pause=500&color=0A84FF&center=true&vCenter=true&width=700&lines=Sarvesh+Kulkarni;ML+Engineer+%7C+On-Device+AI+%7C+Fraud+Detection;Building+Systems+That+Work+in+Production" />
</p>

---

## 🧠 Who I Am

**ML Engineer focused on real-world constraints:**
- Imbalanced datasets (fraud, anomaly detection)
- On-device inference (Android, offline-first systems)
- Multi-label classification problems

I build models that **survive production**, not just notebooks.

---

## ⚡ What I Build

| Domain | Constraint | Approach |
|:--|:--|:--|
| **Fraud Detection** | Extreme class imbalance (≈0.17%) | Optimize **PR-AUC**, not accuracy |
| **On-Device NLP** | Limited memory & compute | Compress models (<2MB), run fully offline |
| **Multi-Label Systems** | Overlapping outputs | OvR strategies + custom preprocessing |

---

## 🧠 Featured Case Studies

<details open>
<summary><b>Credit Card Fraud Detection</b> — High Recall Under Extreme Imbalance</summary>

**Problem**  
Accuracy fails when fraud rate is <1%. Missing fraud is expensive.

**Approach**
- SMOTE for class balancing (1:578 ratio)
- XGBoost optimized on **Precision-Recall AUC**
- Threshold tuning for recall prioritization

**Tech**
`scikit-learn` · `XGBoost` · `pandas`

**Results**
- Recall: **0.92**
- Precision: **0.87**
- PR-AUC: **0.91**
- Latency: **~14ms (CPU)**

</details>

---

<details>
<summary><b>Spam SMS Detection</b> — 1.7MB Model Running Fully Offline</summary>

**Problem**  
Spam detection must work **locally** without sending user data to cloud APIs.

**Approach**
- TF-IDF + Multinomial Naive Bayes
- Feature pruning + hashing for compression
- Deployment via TensorFlow Lite (Android)

**Tech**
`scikit-learn` · `TensorFlow Lite` · `Kotlin`

**Results**
- F1 Score: **0.98**
- Model Size: **1.7MB**
- Inference: **<1ms**
- Offline: **100% local execution**

</details>

---

<details>
<summary><b>Movie Genre Classification</b> — Multi-Label Prediction System</summary>

**Problem**  
Movies belong to multiple genres simultaneously.

**Approach**
- One-vs-Rest Logistic Regression
- Custom text preprocessing pipeline
- Evaluated using Hamming Loss

**Tech**
`scikit-learn` · `pandas`

**Results**
- Hamming Loss: **0.051**
- Exact Match Ratio: **0.62**
- Dataset: **42K+ samples**

</details>

---

## 📊 Proof of Work

<div align="center">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=sarveshkulkarni2023&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="150em" src="https://github-readme-streak-stats.herokuapp.com/?user=sarveshkulkarni2023&theme=tokyonight&hide_border=true" />
</div>

---

## 🏆 Validation

- **Smart India Hackathon Finalist** — Built real-time waste classification system (94% accuracy)
- **GDSC Workshop Lead** — Delivered on-device ML workshop (40+ participants)
- **Consistent GitHub Activity** — Focus on model improvement, not boilerplate

---

## ⚙️ Tech Stack

**Languages**
`Python` · `Java` · `Kotlin`

**Machine Learning**
`scikit-learn` · `XGBoost` · `TensorFlow Lite` · `Pandas` · `NumPy`

**Android**
`Jetpack Compose` · `Room` · `WorkManager`

**Tools**
`Git` · `Jupyter`

---

## 🚧 Currently Building

**Project Hermes — AI-Powered SMS Firewall**

- On-device spam classification
- Privacy-first (no cloud calls)
- Integrated Android SMS client

**Goal:** Production-ready offline AI system

---

## 🎯 Direction

- Short Term: Deploy ML models inside real Android apps  
- Long Term: Focus on **AI security & adversarial robustness on edge devices**

---

## 📬 Contact

- Email: kulkarnisarvesh159@gmail.com 
- LinkedIn:(https://www.linkedin.com/in/sarvesh-kulkarni-723404294/)
- Portfolio:(https://sarvesh564.github.io/MYPortfolio/)

---

<p align="center">
  <sub><b>Signal > Noise | Systems > Projects | Impact > Aesthetics</b></sub>
</p>
