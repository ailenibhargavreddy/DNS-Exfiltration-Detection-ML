# DNS Exfiltration Detection Using Machine Learning

This project detects **DNS data exfiltration attacks** using machine learning models.
The dataset used is **CIC Bell DNS EXF 2021**, created by the Canadian Institute for Cybersecurity.

⚠️ Note:  
**The dataset is copyrighted and cannot be uploaded to GitHub.**  
Users must download it manually from the official website.

---

## 📌 Project Structure

## 📊 Dataset

Dataset used: **CIC Bell DNS Exfiltration 2021**  
Download link:  
https://www.unb.ca/cic/datasets/dns-exf-2021.html

Dataset categories:
- Benign traffic  
- Light exfiltration attacks  
- Heavy exfiltration attacks  

We used:
- 14 Stateless features  
- 16 Stateful features  
- A combined hybrid approach

---

## 🔍 Machine Learning Models Used

| Model | Accuracy | Notes |
|-------|----------|--------|
| Random Forest | ~71% | Best overall |
| XGBoost | ~68% | Lower performance |
| Hybrid Stateful + Stateless | Best theoretical model |

---

## 🚀 How to Run the Project

1. Clone the repository  
2. Install dependencies  
