![Python](https://img.shields.io/badge/Python-3.9-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Last Commit](https://img.shields.io/github/last-commit/AndyWu147/STEM-major-salaries-analysis)
# U.S. College ROI: Analyzing Earnings vs Tuition Using Scorecard Data
**Built With:**  
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter · Git

## 1. Overview  
This project analyzes the **Return on Investment (ROI)** of U.S. colleges using data from the Department of Education’s College Scorecard.  
It evaluates how tuition costs relate to early-career earnings across institutions, school types, and student demographics.

## 2. What This Project Covers  
- Cleaned and merged College Scorecard earnings and institution datasets  
- Calculated ROI for in-state and out-of-state students  
- Labeled schools by STEM focus using the Field-of-Study dataset  
- Created 9 visualizations on ROI distribution, gender/income gaps, school types, tuition–earnings link  
- Produced insights to support families, policymakers, and researchers

## 3. Getting Started

Clone the repo and install the required libraries.

**Steps:**  
1. Clone the repository:  
   `git clone https://github.com/AndyWu147/STEM-major-salaries-analysis.git`  
   `cd STEM-major-salaries-analysis`  

2. Install dependencies (Python 3.9+):  
   `pip install pandas numpy matplotlib`  

3. Open the notebook:  
   Open `notebooks/stem_salaries_analysis.ipynb` in Jupyter and run all cells.  

You can also view the notebook directly on GitHub [here](notebooks/stem_salaries_analysis.ipynb).

## 4. Data Sources  
- [College Scorecard Earnings Data](https://collegescorecard.ed.gov/data/)  
- [College Scorecard Institutional Data](https://collegescorecard.ed.gov/data/)  
- U.S. Department of Education, 2022

## 5. Folder Structure  
STEM-major-salaries-analysis/
│
├── data/ # Raw data files (excluded in .gitignore)
├── notebooks/ # Final notebook (.ipynb)
├── plots/ # Generated plots
├── src/ # Python scripts for data cleaning and analysis
├── README.md
├── LICENSE
└── .gitignore

## 6. Key Insights

### A. ROI Distribution  
ROI is heavily right-skewed. Most schools offer modest ROI, with a small group delivering very high value.

### B. Top 20 In-State ROI Schools  
Mostly public STEM-oriented universities with low tuition and strong wage outcomes. Affordability + technical majors drives high ROI.

### C. Top 20 Out-of-State ROI Schools  
ROI drops sharply for non-residents. Only a few elite public schools remain competitive for out-of-state students.

### D. ROI by School Type  
Public schools have the strongest average ROI. Private nonprofits show wide variability. For-profit colleges consistently underperform.

### E. Male vs Female Earnings Gap  
Males earn more than females at nearly all institutions. The difference is persistent and sizable.

### F. Family Income Group Earnings  
Higher-income families earn more after graduation, even at the same schools. Socioeconomic background significantly affects outcomes.

### G. ROI by State  
States with strong technology ecosystems (CA, MA, TX) show the highest ROI. States with many smaller private colleges show weaker results.

### H. STEM vs Non-STEM School Earnings  
STEM-heavy institutions deliver substantially higher early-career earnings. The gap is large and consistent.

### I. Tuition vs Earnings Relationship  
In-state tuition has only a weak link to alumni earnings a decade later. An R² of 0.30 indicates tuition explains little of the variation in income across institutions.

## 7. Future Improvements

-Add mid-career (10-year) ROI analysis
-Incorporate program-level earnings instead of school-level
-Build an interactive dashboard (Plotly/Streamlit)
-Add machine learning to predict ROI based on school features

## 8. License  
This project is licensed under the MIT License.
