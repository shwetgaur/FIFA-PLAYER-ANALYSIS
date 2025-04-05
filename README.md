# ⚽ FIFA Player Performance Analysis (2015–2020)

## 📌 Project Title
**Dimensionality Reduction and Comparative Analysis using PCA, LDA, SVD, t-SNE, and MDS on FIFA Player Stats**

---

## 👥 Group Members
- **Member 1**: Shwet Gaur
- **Member 2**: Saksham Sharma

---

## 📂 Dataset Overview

This project uses FIFA player statistics from **FIFA 15 to FIFA 20**, compiled in six separate CSV files:
- `players_15.csv`
- `players_16.csv`
- `players_17.csv`
- `players_18.csv`
- `players_19.csv`
- `players_20.csv`

Each file contains detailed attributes about players, such as:
- Player Name, Nationality, Club
- Age, Overall Rating, Potential
- Skill attributes (Dribbling, Passing, Shooting, etc.)
- Physical attributes (Height, Weight, Sprint Speed, etc.)

---

## 🎯 Objective

To explore, reduce, and analyze the dimensionality of high-dimensional FIFA data using multiple unsupervised and supervised dimensionality reduction techniques. The goal is to visualize and compare how well each technique captures structure in the data.

---

## 🛠️ Tools and Technologies

- **Google Colab** / Jupyter Notebook
- **Python Libraries**:
  - `Pandas`, `NumPy`
  - `Matplotlib`, `Seaborn`, `Plotly`
  - `scikit-learn` (PCA, LDA, SVD, t-SNE, MDS)
- **Google Drive** (for file storage and access)

---

## 📁 Project Structure

```bash
FIFA_Dimensionality_Reduction_Project/
├── Datasets/
│   ├── players_15.csv
│   ├── players_16.csv
│   ├── players_17.csv
│   ├── players_18.csv
│   ├── players_19.csv
│   └── players_20.csv
│
├── Notebooks/
│   ├── 1_Dataset_Description.ipynb
│   ├── 2_Preprocessing.ipynb
│   ├── 3_EDA.ipynb
│   ├── 4_Models_DimensionalityReduction.ipynb
│   └── 5_Results_Analysis.ipynb
│
└── README/
    └── Project_Overview.txt


