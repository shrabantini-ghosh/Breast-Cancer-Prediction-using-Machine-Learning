# 🧬 Breast Cancer Classification (Logistic Regression)

This project uses **Machine Learning (Logistic Regression)** to classify breast cancer tumors as **Malignant (cancerous)** or **Benign (non-cancerous)** using the **Wisconsin Breast Cancer Dataset**.  

---

## 📊 Dataset
- **Source:** Wisconsin Breast Cancer Dataset (CSV provided in repo)  
- **Samples:** 569  
- **Features:** 30 tumor characteristics (radius, texture, smoothness, concavity, etc.)  
- **Target:** Diagnosis (`M` = Malignant, `B` = Benign)  

---

## ⚙️ Methodology
1. Data Preprocessing  
   - Removed unnecessary columns (`id`, empty column)  
   - Encoded labels (`M` → 1, `B` → 0)  
   - Applied **StandardScaler** for normalization  

2. Model Training  
   - Algorithm: **Logistic Regression**  
   - Train-Test Split: 80-20  

3. Model Evaluation  
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix (heatmap)  
   - ROC Curve with AUC score  

4. Real-Time Testing  
   - Function `predict_real_time()` allows testing with **custom patient data** (30 features)  

---

## 📈 Results
- Accuracy: **90%+**  
- Precision & Recall both above **90%**  
- Strong AUC score showing reliable classification  

---

## 🚀 How to Run
```bash
# Clone repo
git clone <repo-link>
cd breast-cancer-classification

# Install dependencies
pip install -r requirements.

# Run the project
python breast_cancer.py
