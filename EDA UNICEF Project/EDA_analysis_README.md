# 🎓 Early Risk Detection in Student Performance – EDA for UNICEF

## 📌 Project Overview

This project explores how social, economic, and educational conditions affect student performance in mathematics. Using real student data, the goal is to identify risk factors that contribute to academic underachievement.

Originally developed as an academic exercise, this project is reframed to support non-profit organizations such as **UNICEF** or local education departments in designing data-driven intervention strategies.

---

## 🎯 Business Problem

**How can we identify students at risk of underperforming in school early enough to intervene effectively?**

By analyzing key behavioral and socio-economic indicators (e.g., absences, parental education, support systems), we aim to extract actionable insights that education-focused NGOs can use to:

- Detect high-risk students
- Allocate tutoring and mentorship resources
- Inform education policy and support planning

---

## 📊 Dataset

The dataset contains information on 395 students with 30 features, including:

- **Demographics:** Age, gender, address type
- **Education-related:** Study time, past failures, absences, parental education
- **Social:** Family support, school support, relationships
- **Target variable:** `score` (final math grade)

---

## 🧪 Project Workflow

1. **Data Cleaning & Preprocessing**
   - Checked for missing or inconsistent data
   - Categorized variables as numerical or categorical
   - Handled outliers using IQR-based filtering

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots, boxplots, and heatmaps
   - Comparison of group means using Student's t-tests
   - Identification of statistically significant factors affecting scores

3. **Key Metrics Explored**
   - Impact of absences, parental education, support availability
   - Gender and age group comparisons
   - Influence of living situation on academic performance

---

## 💡 Key Findings

| Factor | Insight | Actionable Suggestion |
|--------|---------|------------------------|
| Absences | High absences correlate strongly with low scores | Attendance tracking and intervention |
| Family support | Lack of support reduces scores by ~10–15% | School-parent engagement programs |
| Study time | Low weekly study time often leads to underperformance | Personalized tutoring |

---

## 📌 Next Steps (Future Work)

- Integrate **predictive modeling** (e.g., classification for risk detection)
- Build a **dashboard** for real-time analysis of student profiles
- Apply **clustering** to segment students into risk categories

---

## 📁 File Structure

```
📦 EDA_for_UNICEF
 ┣ 📄 EDA_for_UNICEF.ipynb         # Main analysis notebook
 ┣ 📄 EDA_analysis_README.md       # Project summary and context
 ┗ 📄 stud_math.csv                # Source dataset
```

---

## 🤝 Stakeholders

This project is designed for:
- NGOs focused on youth and education (e.g., UNICEF)
- School administrators and policymakers
- Data scientists working in public sector education

---

## 🧠 Author

**Andrii Mazur**  
Data Science Portfolio Project  
[GitHub Profile](https://github.com/mazurandrii92)

---

## 📬 Contact

For collaboration or questions, feel free to connect via GitHub or LinkedIn.
