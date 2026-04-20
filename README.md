# 🎓 Student Placement Analytics Dashboard

An Excel-based interactive dashboard analyzing placement outcomes, salary trends, and career patterns for **5,000 engineering students** across multiple branches, college tiers, and skill profiles.

---

## 📊 Dashboard Overview

This workbook provides a multi-sheet analytical dashboard built entirely in Microsoft Excel, offering pivot-table-driven insights into student placement data. It is designed to help academic institutions, placement cells, and researchers understand the factors that influence student employment outcomes.

---

## 📁 File Structure

| Sheet | Description |
|-------|-------------|
| `overview` | High-level summary and navigation |
| `BRANCH` | Placement analysis segmented by engineering branch |
| `experience` | Impact of internships and projects on placement |
| `salary` | Salary package distribution and averages |
| `TABLES` | Raw pivot tables powering the dashboard |
| `DATA` | Complete student dataset (5,000 rows) |

---

## 🗂️ Dataset Description

The `DATA` sheet contains one row per student with the following fields:

| Column | Description |
|--------|-------------|
| `branch` | Engineering branch (CSE, ECE, IT, CE, ME, aiml, data science) |
| `STUDENT_ID` | Unique student identifier |
| `college_tier` | Institution tier (Tier-1, Tier-2, Tier-3) |
| `cgpa` | Cumulative GPA (scale: ~4.2 – 10.0) |
| `backlogs` | Number of academic backlogs |
| `coding_skills` | Coding proficiency score (0–10) |
| `dsa_score` | Data structures & algorithms score (0–10) |
| `aptitude_score` | Aptitude test score (0–100) |
| `communication_skills` | Communication score (0–10) |
| `ml_knowledge` | Machine learning knowledge score (0–10) |
| `system_design` | System design score (0–10) |
| `internships` | Number of internships completed |
| `projects_count` | Number of projects completed |
| `certifications` | Number of certifications earned |
| `hackathons` | Number of hackathons participated in |
| `open_source_contributions` | Number of open-source contributions |
| `extracurriculars` | Extracurricular activity count |
| `placement_status` | Placed (1) or Not Placed (0) |
| `salary_package_lpa` | Salary offered in Lakhs Per Annum (LPA) |
| `coding_bucket` | Coding skill category (Low, Med, Good, High) |
| `Interested_Career_Area` | Preferred career domain |
| `Suggested_Job_Role` | Recommended job role |
| `Preferred_Company_Type` | Preferred employer type |
| `cgpa range` | CGPA bracket |

---

## 📈 Key Metrics & Insights

### Placement Rate
- **Total Students:** 5,000
- **Placed:** 3,427 (68.5%)
- **Not Placed:** 1,573 (31.5%)

### Salary by College Tier (Average LPA)
| Tier | Avg. Salary (LPA) |
|------|-------------------|
| Tier-1 | ₹16.12 |
| Tier-2 | ₹12.44 |
| Tier-3 | ₹9.98 |

### Salary by Branch (Average LPA)
| Branch | Avg. Salary (LPA) |
|--------|-------------------|
| IT | ₹12.68 |
| CSE | ₹12.59 |
| Data Science | ₹11.26 |
| ME | ₹11.70 |
| ECE | ₹11.69 |
| CE | ₹11.00 |
| AI/ML | ₹11.00 |

### Placement Rate by Branch
| Branch | Placement Rate |
|--------|---------------|
| IT | 73% |
| CSE | 72% |
| Data Science | 66% |
| ECE | 67% |
| CE | 63% |
| AI/ML | 64% |
| ME | 68% |

### Student Distribution by Preferred Company Type
| Company Type | Count |
|-------------|-------|
| Product-Based | 873 |
| Service-Based | 859 |
| Government | 853 |
| Startup | 819 |
| Remote/Abroad | 811 |
| MNC | 785 |

### Student Distribution by Career Interest
| Career Area | Count |
|-------------|-------|
| Cyber Security | 868 |
| Web Development | 866 |
| Cloud Computing | 829 |
| Data Science | 825 |
| Business Analytics | 819 |
| AI/ML | 793 |

### Placement Rate by Experience (Internships)
Higher internship count correlates strongly with improved placement odds — students with 9–10 internships achieved an ~82% placement rate vs. ~59% for those with just 1–2.

### Placement Rate by Coding Skill Bucket
| Coding Skill | Placement Rate |
|-------------|---------------|
| High (7–10) | ~77% |
| Good (5–7) | ~67% |
| Med (3–5) | ~63% |
| Low (0–3) | ~59% |

---

## 🛠️ How to Use

1. **Open** `EXCEL_DASHBOARD.xlsx` in Microsoft Excel (2016 or later recommended).
2. Navigate to the **`overview`** sheet for the main dashboard.
3. Use the **`BRANCH`**, **`experience`**, and **`salary`** sheets to explore targeted analyses.
4. The **`TABLES`** sheet contains all underlying pivot tables — avoid editing these directly.
5. The **`DATA`** sheet is the source data. You can apply filters or slicers for custom exploration.

> ⚠️ **Note:** Macros are not required. All visualisations and summaries are formula- and pivot-table-driven.

---

## 📋 Requirements

- Microsoft Excel 2016 or later (for full pivot table and slicer support)
- Compatible with Excel for Microsoft 365

---

## 📌 Use Cases

- **Placement Cells:** Identify at-risk students and target support interventions
- **Academic Research:** Study the relationship between skills, tier, and employability
- **Career Counselling:** Match students to optimal roles and company types based on their profile
- **Institutional Benchmarking:** Compare placement outcomes across branches and tiers

---

## 📄 License

This project is for educational and analytical purposes. Please credit appropriately if used in research or presentations.
