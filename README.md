# Association Between Types of Fever and Age Group using Randomized Block Design (RBD)

📊 **Statistical Analysis Project | Final Minor Project (2024–25)**  
🎓 Department of Statistics, Pratibha College of Commerce and Computer Studies, Chinchwad  
👨‍🎓 Aarif Siddique, 👩‍🎓 Kalyani Garud, 👩‍🎓 Vrushali Kale  
📘 Supervised by: Dr. Jayashree Muley

---

## 📚 Project Description

This project explores the **association between age groups and types of fever** using statistical methods like **Chi-square test** and **Randomized Block Design (RBD)**. The goal is to identify patterns in fever cases across different age groups and use statistical analysis to draw meaningful, data-driven healthcare conclusions.

---

## 🎯 Objectives

- 🔍 Identify which **age groups** are most affected by specific **types of fever**.
- 📊 Analyze the **distribution** and **severity** of fever cases using statistical methods.
- 🏥 Provide **insights** for hospitals and public health authorities.
- 🧪 Suggest targeted **preventive strategies** based on data trends.

---

## 🦠 Fever Types Considered

1. **Viral Fever**
2. **Enteric Fever (Typhoid)**
3. **Dengue**
4. **Influenza-like Illness (ILI)**
5. **NAD (No Abnormality Detected)**

---

## 👥 Age Groups Analyzed

- 14–23 years  
- 24–33 years  
- 34–43 years  
- 44–53 years  
- 54–63 years  
- 64+ years

---

## 🧪 Methodology

### 1. **Chi-square Test of Independence**
- Used to test the association between age group and fever type.
- Result: p-value ≈ 8.92 × 10⁻¹⁶³ ⇒ Significant association found.

### 2. **Randomized Block Design (RBD)**
- Blocks: Age Groups
- Treatments: Types of Fever
- RBD ANOVA → Significant differences found between both age groups and fever types.

### 3. **Post-Hoc Tests**
- **Critical Difference (CD) Test**
- **Tukey’s HSD**
- **Scheffé’s Test**

These tests help determine which fever types significantly differ across age groups.

---

## 📊 Key Findings

- **NAD and ILI are most prevalent**, especially in older age groups.
- **Viral, Enteric, and Dengue fevers** show increased frequency with age.
- **Influenza-like Illness (ILI)** is more common in younger age groups.
- **Dengue & ILI** show similar patterns across age groups (no significant difference).
- Age and fever type both significantly affect fever distribution.

---

## 🏥 Real-World Applications

- **Hospital Planning**: Optimize bed allocation, resources, and staff.
- **Public Health**: Run targeted awareness campaigns for vulnerable age groups.
- **Policy-Making**: Formulate age-specific healthcare interventions.
- **Data Science**: Foundation for AI-based outbreak prediction models.

---

## 📂 Project Structure

```bash
├── README.md
├── data/
│   └── fever_cases_by_age.csv         # Tabular dataset used in analysis
├── analysis/
│   ├── chi_square_analysis.xlsx       # Chi-square and expected values
│   ├── rbd_anova_results.xlsx         # RBD and ANOVA outputs
│   └── post_hoc_tests.xlsx            # CD, Tukey, and Scheffé test results
├── visuals/
│   ├── bar_charts.png
│   └── summary_tables.png
└── report/
    └── Final_Minor_Project_Report.pdf

🛠️ Tools & Technologies
📊 MS Excel for ANOVA and Post-Hoc testing

🧮 Descriptive and Inferential Statistics

🧾 Randomized Block Design (RBD)

📈 Graphical Visualization (bar plots, tables)

🔮 Future Scope
Integrate machine learning models to forecast fever trends.

Use larger datasets from hospitals or government portals.

Expand scope to seasonal analysis or geographical clustering.

📖 References
World Health Organization (WHO)

Centers for Disease Control and Prevention (CDC)

Indian Council of Medical Research (ICMR)

National Center for Biotechnology Information (NCBI)

Government of India Health Reports

🙌 Acknowledgements
We thank:

Savitribai Phule Pune University

Dr. Jayashree Muley (Project Guide and HOD)

Kamala Education Society & Pratibha College

Our families, peers, and library staff for their constant support.

📬 Contact
For queries, collaborations, or feedback:

📧 aarif.siddique@email.com

💼 LinkedIn – https://www.linkedin.com/in/aarifsiddiqui
