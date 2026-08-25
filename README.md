# 📊 Job Market Data Analysis 2026

An exploratory data analysis (EDA) project analyzing tech job market trends, salary distributions, remote work preferences, and in-demand technical skills for 2026.

## 📌 Project Overview
This project provides actionable insights into compensation structures and tech job availability based on dataset analysis (`job_market_2026.csv`). The analysis is documented step-by-step in the Jupyter notebook `Job_Market_Analysis.ipynb`.

### Key Objectives
1. **Data Cleaning & Preprocessing**: Handling missing values, data type conversions, and missing salary imputations.
2. **Salary Insights**: Analyzing salary distributions by experience level, job role, and location.
3. **Remote Work Trends**: Comparing compensation across On-site (0%), Hybrid (50%), and Fully Remote (100%) roles.
4. **In-Demand Skills Analysis**: Identifying top technical skills requested by employers across tech roles.

---

## 📁 Repository Structure
```
data-analysis-mini-project/
│── Job_Market_Analysis.ipynb   # Main Jupyter Notebook with code & visual analysis
│── job_market_2026.csv          # Dataset containing job market metrics
│── experience_salary.png        # Salary vs Experience visual
│── jobs_by_loaction.png         # Job postings distribution by location
│── remote_work_analysis.png     # Work arrangement & compensation distribution
│── salary_by_role.png           # Salary distribution by job role
│── skills_analysis.png          # Top technical skills in demand
│── top_job_roles.png            # Most frequent job postings
│── .gitignore                   # Git ignore file
└── README.md                    # Project documentation
```

---

## 🛠 Tech Stack & Libraries
- **Language**: Python 3.x
- **Environment**: Jupyter Notebook
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Notebook
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate into the project folder:
   ```bash
   cd "data analysis mini project"
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Job_Market_Analysis.ipynb
   ```

---

## 📈 Visual Highlights
The notebook includes detailed visualizations covering:
- **Salary by Experience Level**
- **Median Compensation across Roles**
- **Remote Work Distribution**
- **Top Demanded Technical Skills**

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
