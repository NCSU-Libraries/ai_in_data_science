<div align="center">

<a href="https://www.lib.ncsu.edu/" aria-label="nc state university libraries logo"><img src="assets/lib_logo_whiteBG.svg" width="400" alt="NC State University Libraries Logo" /></a>

<h2>NC State University Libraries Python Workshops</h2>

<a href="https://www.lib.ncsu.edu/workshops"><img alt="NC State Libraries Workshops" src="https://img.shields.io/badge/NC%20State%20Libraries-Workshops-red"></a>
<a href="https://www.lib.ncsu.edu/staff/department/data-science-services"><img alt="Data Science Services" src="https://img.shields.io/badge/Data%20Science%20Services-Libraries-red"></a>
<a href="https://go.ncsu.edu/getdatahelp"><img alt="GetDataHelp" src="https://img.shields.io/badge/Get%20Data%20Help-go.ncsu.edu%2Fgetdatahelp-red"></a>
<a href="mailto:getdatahelp@ncsu.edu"><img alt="Email: getdatahelp@ncsu.edu" src="https://img.shields.io/badge/Email-getdatahelp%40ncsu.edu-red"></a>
<br/>

</div>

# Emergency Room Wait Time Data Analysis

## 📓 Notebooks Available

### 🎓 Educational Template (Recommended for Learning)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NCSU-Libraries/ai_in_data_science/blob/main/er_wait_time_data.ipynb)

**`er_wait_time_data.ipynb`** - Interactive learning template with:
- Step-by-step instructions
- Educational descriptions
- Accessibility features
- Placeholder cells for student work

### 📊 Completed Analysis (Reference)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NCSU-Libraries/ai_in_data_science/blob/main/er_wait_time_data_filled.ipynb)

**`er_wait_time_data_filled.ipynb`** - Complete analysis with:
- All code executed with results
- Full visualizations and outputs
- Statistical test results
- Comprehensive analysis conclusions

## 📊 Overview

This repository contains a comprehensive analysis of Emergency Room (ER) wait time data, designed for educational purposes. The notebook demonstrates data science techniques including exploratory data analysis, statistical testing, and data visualization using Python.

## 🎯 Learning Objectives

By completing this analysis, you will learn to:
- Load and inspect healthcare datasets
- Perform exploratory data analysis (EDA)
- Apply statistical tests to healthcare data
- Create meaningful visualizations
- Draw actionable conclusions from data

## 📋 Prerequisites

- Basic Python knowledge
- Familiarity with pandas, matplotlib, and seaborn
- Google Colab account (recommended) or Jupyter environment

## 🚀 Quick Start

### Option 1: Open in Google Colab (Recommended)
Click the "Open In Colab" badge above to run the notebook directly in your browser.

### Option 2: Local Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/NCSU-Libraries/ai_in_data_science.git
   cd ai_in_data_science
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter:
   ```bash
   jupyter notebook er_wait_time_data.ipynb
   ```

## 📚 Dataset Information

- **Source**: NCSU Libraries AI in Data Science Repository
- **Dataset**: ER Wait Time Dataset
- **Format**: CSV, Excel
- **Features**: Patient demographics, wait times, satisfaction ratings, temporal factors

## 🔧 Required Packages

```
pandas >= 2.0.0
numpy >= 1.24.0
matplotlib >= 3.7.0
seaborn >= 0.12.0
scipy >= 1.10.0
statsmodels >= 0.14.0
jupyter >= 1.0.0
openpyxl >= 3.1.0
```

## 📖 Notebook Contents

### 1. Data Acquisition & Loading
- Downloading data from GitHub repository
- Loading CSV data into pandas DataFrame
- Initial data inspection and quality assessment

### 2. Exploratory Data Analysis
- Patient satisfaction analysis
- Temporal patterns (time of day, season)
- Wait time consistency analysis
- Statistical relationships

### 3. Statistical Analysis
- Mann-Whitney U tests
- ANOVA testing
- Correlation analysis
- Effect size calculations

### 4. Data Visualization
- Bar charts and pie charts
- Heatmaps and box plots
- Interactive visualizations
- Statistical plots

## 📚 How to Use These Notebooks

### For Students (Learning)
1. **Start with the template**: Use `er_wait_time_data.ipynb`
2. **Follow the instructions**: Complete each cell step by step
3. **Reference the filled version**: Check `er_wait_time_data_filled.ipynb` if you get stuck
4. **Focus on learning**: The template is designed for educational purposes

### For Instructors (Teaching)
1. **Use the template**: `er_wait_time_data.ipynb` for classroom instruction
2. **Reference the filled version**: `er_wait_time_data_filled.ipynb` for answer key
3. **Customize as needed**: Modify the template for your specific course requirements
4. **Accessibility features**: Built-in support for diverse learning needs

### For Researchers (Reference)
1. **Use the filled version**: `er_wait_time_data_filled.ipynb` for complete analysis
2. **Review methodology**: See the statistical approaches used
3. **Adapt the code**: Modify for your own datasets
4. **Cite appropriately**: Follow the citation guidelines in the notebook

## 🎯 Notebook Comparison

| Feature | Template (`er_wait_time_data.ipynb`) | Filled (`er_wait_time_data_filled.ipynb`) |
|---------|--------------------------------------|-------------------------------------------|
| **Purpose** | Learning and teaching | Reference and research |
| **Code Execution** | Students run cells | Pre-executed with results |
| **Outputs** | Students generate | Complete outputs included |
| **Accessibility** | Full accessibility guide | Accessibility guide included |
| **Educational Content** | Step-by-step instructions | Complete analysis |
| **Best For** | Classroom instruction | Research reference |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.