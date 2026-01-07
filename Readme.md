
# Holiday Package Predict

This project focuses on predicting whether a customer will purchase a holiday package using a **Random Forest Classifier**.  
The model is trained on customer demographic and behavioral data to assist businesses in targeted marketing and decision-making.

---

## Project Structure

- **Travel.csv** – Dataset containing customer details and target labels  
- **forest_classifier.ipynb** – Jupyter Notebook with data preprocessing, model training, and evaluation  
- **auc.png** – AUC performance visualization  

---

## Objective

To build a machine learning classification model that predicts holiday package purchase likelihood using customer attributes.

---

## Dataset

The dataset includes:
- Customer demographics
- Travel-related attributes
- Target variable indicating package purchase (Yes/No)

Detailed feature explanations are available inside the notebook.

---

## Model Used

- **Random Forest Classifier**
  - Handles non-linear relationships
  - Robust to outliers
  - Provides feature importance

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Naman0911/Holiday-Package-Predict.git
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. Open the notebook:
   ```bash
   jupyter notebook forest_classifier.ipynb
   ```

---

## Evaluation

- Model performance evaluated using **AUC**
- Visualization available in `auc.png`

---

## License

This project is open-source and intended for educational purposes.
