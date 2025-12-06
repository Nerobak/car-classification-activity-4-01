# Activity 4.01 – Car Data Classification  
Decision Tree Classifier (Packt Dataset)

This repository contains the Jupyter Notebook for **Activity 4.01** from  
*The Applied Artificial Intelligence Workshop* (Packt Publishing).

The goal of this activity is to build a **Decision Tree classification model** that predicts the acceptability level of a car based on several categorical features.

---

## 📊 Dataset  
The dataset used in this activity comes from the Packt GitHub repository:


https://raw.githubusercontent.com/PacktWorkshops/The-Applied-Artificial-Intelligence-Workshop/master/Datasets/car.csv

It includes the following features:

- `buying`
- `maintenance`
- `doors`
- `persons`
- `luggage_boot`
- `safety`

Target variable:

- `class` → {unacc, acc, good, vgood}

All columns are **categorical**, so label encoding is applied before training.

---

## 🧠 Steps Performed in the Notebook

1. **Load the dataset** using `pandas.read_csv()`
2. **Encode categorical variables** using `LabelEncoder`
3. **Separate features and target** (using `df.pop("class")`)
4. **Split the dataset** into training/testing using `train_test_split`
5. **Build a Decision Tree classifier** using `DecisionTreeClassifier`
6. **Evaluate model performance** with accuracy
7. **Generate a Classification Report**  
   (precision, recall, F1-score, support)

---

## 🧪 Technologies Used

- Python  
- Jupyter Notebook  
- pandas  
- scikit-learn  

---

## 📁 File in This Repository

| File | Description |
|------|-------------|
| `Car_Classification.ipynb` | Main notebook containing all code, explanations, and results |

---

## 📌 How to Run the Notebook

1. Open Jupyter Notebook or JupyterLab  
2. Upload this notebook or clone the repo  
3. Run the cells in order  
4. Ensure internet access (dataset loads from GitHub URL)

---

## ✅ Status  
This repository fulfills the assignment requirement:  
**Deliver only the Jupyter Notebook and the link to this GitHub repo.**

---

## ✉️ Contact  
If you have questions or feedback, feel free to reach out.

