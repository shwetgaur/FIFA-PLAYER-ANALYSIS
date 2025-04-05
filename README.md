# ⚽ FIFA Player Performance Analysis (2015–2020)

## 📌 Project Title
**Dimensionality Reduction and Comparative Analysis using PCA, LDA, SVD, t-SNE, and MDS on FIFA Player Stats**

---

## 👥 Group Members
- **Member 1**: Your Name (Roll Number)
- **Member 2**: Partner Name (Roll Number)

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
📊 Notebooks & Content
1_Dataset_Description.ipynb
Overview of all CSV files

Description of attributes

Comparison of features across years

2_Preprocessing.ipynb
Cleaning missing values

Selecting relevant numeric features

Feature scaling using StandardScaler

Merging datasets for analysis

3_EDA.ipynb
Distribution plots, correlation heatmaps

Trend analysis of player ratings across years

Top player analysis by year and country

4_Models_DimensionalityReduction.ipynb
Applied: PCA, LDA, SVD, t-SNE, MDS

Visualization using 2D/3D plots

Explained Variance, Cluster formation, and Separation

5_Results_Analysis.ipynb
Performance summary of each technique

Comparison of interpretability, cluster quality

Final insights and recommendations

📈 Key Findings
PCA and t-SNE offered the most meaningful cluster separation.

LDA worked well when class labels like player positions were used.

t-SNE revealed non-linear clusters, ideal for visual interpretation.

SVD retained structure but didn’t perform well visually.

MDS was computationally expensive but useful for similarity-based projections.

🚀 How to Run
Clone or download this repository.

Open the notebooks in Google Colab or Jupyter.

Upload the CSV files to your Drive or Colab session if not using mounted Drive.

Run the notebooks in order (1 → 5) for a full walkthrough.

🧠 Skills Demonstrated
Data Cleaning and Feature Engineering

Dimensionality Reduction Techniques

Comparative Model Evaluation

Data Visualization and Interpretation
