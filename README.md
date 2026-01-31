# H1B Immigration Data Visualization Project

A comprehensive data visualization project analyzing H1B visa petition data from FY2020 to FY2024, created as part of a data visualization course at Indiana University Bloomington.

## 📊 Project Overview

This project explores and visualizes trends in H1B immigration petitions, including analysis by:
- Geographic distribution
- Gender demographics
- Country of birth statistics
- Temporal trends across fiscal years

## 📁 Project Contents

### Main Analysis
- **visualization.ipynb** - Primary Jupyter notebook containing all data analysis and visualizations

> **Note:** This repository contains the notebook with outputs cleared to reduce file size. After cloning and obtaining the datasets, run all cells to generate the visualizations.

### Documentation
- **data visualisation report.pdf** - Comprehensive project report
- **DATA VIZ PROJECT INDIANA UNIVERSITY BLOOMINGTON PPT.pptx** - Project presentation

### Reference Materials
- **h-1b-petitions-by-gender-country-of-birth-fy2019.pdf** - Background reference data

## 📦 Dataset Information

The project uses several large datasets (not included in this repository due to size):

| Dataset | Description | Size |
|---------|-------------|------|
| `Combined_LCA_Disclosure_Data_FY2020_to_FY2024.csv` | Raw LCA disclosure data | 2.8 GB |
| `preprocessed_lca_data.csv` | Cleaned and preprocessed data | 722 MB |
| `H1b_full_cleaned.csv` | Full cleaned H1B petition data | 78 MB |
| `Map_data.csv` | Geographic mapping data | 2 KB |
| `US Immigration Statistics (Ver 1.7.23).csv` | Summary statistics | 3 KB |

> **Note:** Due to GitHub file size limitations, CSV datasets are not included in this repository. You can download the original data from the [Department of Labor LCA Disclosure Data](https://www.dol.gov/agencies/eta/foreign-labor/performance).


## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Git with Git LFS (Large File Storage) installed
- Required libraries (see Requirements section)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/data-viz-project.git
cd data-viz-project
```

> **Note:** This repository uses Git LFS for the large Jupyter notebook file. Make sure you have Git LFS installed before cloning.

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Download the datasets from the [Department of Labor LCA Disclosure Data](https://www.dol.gov/agencies/eta/foreign-labor/performance) and place them in the project directory.

4. Launch Jupyter Notebook:
```bash
jupyter notebook visualization.ipynb
```

## 📚 Requirements

The project uses the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- jupyter

## 📧 Contact

For questions or collaboration opportunities, please reach out through GitHub.

## 🎓 Academic Context

This project was completed as part of a Data Visualization course at Indiana University Bloomington.

---

**Keywords:** H1B, Immigration, Data Visualization, Python, Jupyter, Pandas, Geographic Analysis
