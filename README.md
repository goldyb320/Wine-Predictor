# 🍷 Wine Quality Predictor

This project explores the chemical properties that influence wine quality using a real-world dataset from the UCI Machine Learning Repository. The dataset includes red and white Portuguese wines and is analyzed using Python libraries like `pandas`, `seaborn`, and `matplotlib` in a Jupyter Notebook.

---

## 📁 Project Structure

winePredictor/
├── data/
│ ├── winequality-red.csv
│ ├── winequality-white.csv
│ └── winequality.names.txt
├── visuals.py # Custom plotting functions used in the notebook
├── game-of-wines.ipynb # Main analysis notebook
├── game-of-wines.html # Exported HTML version of the notebook
├── game-of-wines-report.html # Report summary (optional or generated)
├── requirements.txt # Python dependencies
├── README.md # Project documentation (this file)

---

## 📊 Features

- Loads and analyzes wine datasets with `pandas`
- Classifies wine quality into three tiers (good, average, poor)
- Visualizes feature relationships using scatter plots, histograms, and heatmaps
- Detects and filters outliers using Tukey’s method
- Includes a complete `visuals.py` helper file for reusable plots

---

## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/winePredictor.git
cd winePredictor
2. Create a Virtual Environment (recommended)
python3 -m venv env
source env/bin/activate  # For WSL or Mac
.\env\Scripts\activate   # For Windows CMD/PowerShell
3. Install Dependencies
pip install -r requirements.txt
4. Launch Jupyter Notebook
jupyter-notebook

Then open game-of-wines.ipynb in your browser.

🧪 Data Source
Wine Quality Datasets (Red & White):
UCI Machine Learning Repository

🧠 Author
By Ashwin Hariharan.
Modified and extended by Ben Goldman.
