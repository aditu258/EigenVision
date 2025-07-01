# 🚀 EigenVision
> **EigenVision**: Unlocking the power of computer vision with Python and Jupyter Notebooks.

---

## 🖼️ Project Overview
EigenVision is a practical demonstration of digit recognition using the MNIST dataset, Principal Component Analysis (PCA), and K-Nearest Neighbors (KNN) in Python.

---

## 📊 Project Overview
This project walks through the process of classifying handwritten digits from the MNIST dataset using:
- Data loading and visualization
- Data preprocessing (standardization)
- Dimensionality reduction with PCA
- Classification with K-Nearest Neighbors (KNN)
- Model evaluation and visualization of results

All code and analysis are contained in the Jupyter notebook: `EigenVision.ipynb`.

---

## 📁 Data
- **File Used:** `train.csv` (downloaded manually and loaded from local path)
- **Shape:** 42,000 samples × 785 columns (1 label + 784 pixel values)

---

## 🛠️ Workflow
1. **Data Loading:**
   - The MNIST training data is loaded from a local CSV file.
   - Data is split into features (`X`) and labels (`y`).

2. **Visualization:**
   - Individual digit images are visualized using matplotlib.

3. **Train-Test Split:**
   - Data is split into training and test sets (80/20 split).

4. **KNN Baseline:**
   - A KNN classifier is trained on the raw pixel data.
   - Baseline accuracy is computed.

5. **Standardization:**
   - Features are standardized using `StandardScaler`.

6. **PCA:**
   - Dimensionality is reduced using PCA (first to 200, then to 2 and 3 components for visualization).
   - Explained variance and eigenvectors are analyzed.

7. **KNN on PCA Data:**
   - KNN is retrained on PCA-transformed data.
   - Accuracy is evaluated again.

8. **Visualization:**
   - 2D and 3D scatter plots of the PCA-transformed data are created using Plotly.
   - Cumulative explained variance is plotted.

---

## 🏆 Results
- **KNN on raw data:** ~96.5% accuracy
- **KNN on PCA (200 components):** ~95.1% accuracy
- **PCA Visualization:**
  - 2D and 3D scatter plots show digit separation in reduced space.
  - Cumulative explained variance plot demonstrates how many components are needed to capture most variance.

---

## 📦 Requirements
- Python 3.13+
- pandas
- numpy
- scikit-learn
- matplotlib
- plotly

Install requirements with:
```bash
pip install pandas numpy scikit-learn matplotlib plotly
```

---

## 📂 Files
- `EigenVision.ipynb` — Main notebook with all code, plots, and results
- `train.csv` — MNIST training data (not included, download from Kaggle)

---

## 🚀 How to Run
1. Download `train.csv` from Kaggle and place it in the appropriate path (update the path in the notebook if needed).
2. Open `EigenVision.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells to reproduce the analysis and results.

---

## 📄 License
This project is licensed under the MIT License.

---

## 📬 Contact
**Project Maintainer:** Aditya Sinha  
