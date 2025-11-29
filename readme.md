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
3. 
Each folder must contain CSV feature files from the dataset.

---

## ▶️ How to Run the Project

1. Download the dataset from the CIC website  
2. Extract the CSV files into the correct folders  
3. Open the notebook:


4. Run all cells sequentially  
5. The model will train and show:
   - Accuracy  
   - Classification report  
   - Confusion matrix  

---

## 📈 Results

Random Forest (best model):

- **Accuracy:** ~71%
- **High recall** for heavy attacks
- **Model handles imbalanced classes reasonably well**

Confusion matrix and metrics are available inside the notebook.

---

## 🔒 Why Dataset Is Not Included

The dataset belongs to the **Canadian Institute for Cybersecurity (CIC)**.

You *must not* upload:
- CSVs  
- PCAPs  
- Benign / attack folders  

Only a small sample (5–10 rows) is legally allowed.

---

## 📚 Citation (Required for Research Use)


---

## 📝 License

This project is for **educational and research purposes only**.  
Dataset is owned by **CIC**.  
Model and code created by **Bhargav Reddy**.

---


