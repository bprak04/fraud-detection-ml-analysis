# fraud-detection-ml-analysis
Machine learning-based fraud detection on imbalanced credit card transaction data using Python and visualization in Tableau
# fraud-detection-ml-analysis

Machine learning-based fraud detection on imbalanced credit card transaction data using Python and visualization in Tableau.

## 📁 Dataset

- 📂 [Download Datasets from Google Drive](https://drive.google.com/drive/folders/1RjDgwxW__U9omdfiRBdMaKx1Jb3S7HZ4?usp=drive_link)
- Source: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 🔧 Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn
- Tableau (for visualization)

## 📊 Key Steps

1. **Data Cleaning**
   - Removed duplicates and handled outliers in `Amount`
   - Dropped `Time` column

2. **Feature Engineering**
   - Created `High_Amount_Flag` feature
   - Scaled `Amount` with `StandardScaler`

3. **Modeling**
   - Random Forest and XGBoost classifiers
   - Evaluated with Confusion Matrix, Classification Report, ROC-AUC

4. **Export & Visualization**
   - Cleaned data exported to CSV for Tableau
   - Visualized fraud trends by amount, flag, and class

## ✅ Results

- **Random Forest ROC-AUC**: ~0.97
- **XGBoost**: High precision on fraud class

---

### 👤 Author

Prakhyath Boinpally  
🔗 [LinkedIn](#) | 💼 [Portfolio](#)
