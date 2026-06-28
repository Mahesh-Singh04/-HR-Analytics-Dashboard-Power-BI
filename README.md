# -HR-Analytics-Dashboard-Power-BI
# 📊 HR Analytics Dashboard — Power BI

> An interactive Power BI dashboard to analyze employee attrition and workforce trends across an organization.

---

## 🖼️ Dashboard Preview

![HR Analytics Dashboard]

---<img width="524" height="298" alt="HR_Analytics_dashboard_img" src="https://github.com/user-attachments/assets/ed105d52-03f5-4cae-a47b-f28baad0112b" />


## 📌 Project Overview

This **HR Analytics Dashboard** was built entirely in **Power BI** to help visualize and understand employee attrition. The dataset contains **1,470 employee records** covering demographics, job roles, salaries, education, and tenure.

**The dashboard answers key HR questions like:**

- Which departments and job roles have the highest attrition?
- Does salary impact employee attrition?
- Which age group is most likely to leave?
- How does tenure at the company affect attrition?

---

## 🎯 Problem Statement

Employee attrition is a costly challenge for any organization — it leads to higher recruitment costs, loss of knowledge, and lower team productivity. This dashboard was built to **identify attrition patterns** and help HR teams make **data-driven decisions** to retain talent.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
| --- | --- |
| Power BI Desktop | Data cleaning, transformation, DAX measures, dashboard design |
| Power Query | Data shaping and transformation |
| DAX | Custom KPI calculations and measures |
| Dataset (.csv) | Raw HR employee data — 1,470 records |

> Everything from raw data to final dashboard was done entirely inside Power BI — no external tools used.

---

## 📂 Dataset Details

- **Source:** HR Employee Attrition Dataset
- **Total Records:** 1,470 employees
- **Active Employees:** 1,413
- **Attrition Count:** 229

**Key columns used:**

| Column | Description |
| --- | --- |
| Age | Employee age |
| Attrition | Whether the employee left (Yes / No) |
| Department | Human Resources / R&D / Sales |
| Job Role | Role within the organization |
| Monthly Income | Salary (in thousands) |
| Education Field | Academic background |
| Years at Company | Tenure in years |
| Gender | Male / Female |
| Job Satisfaction | Rating on a scale of 1 to 4 |

---

## 📊 Dashboard Features

### KPI Summary Cards

| Metric | Value |
| --- | --- |
| Total Employees | 1,413 |
| Attrition Count | 229 |
| Attrition Rate | 16.2% |
| Average Age | 37 years |
| Average Salary | 6.5K / month |
| Avg Years at Company | 7.0 years |

---

### Charts & Visuals

**1. Attrition by Gender**

| Gender | Count |
| --- | --- |
| Male | 136 |
| Female | 76 |

---

**2. Attrition by Education Field**

| Education Field | Share |
| --- | --- |
| Life Sciences | 41% |
| Medical | 31% |
| Marketing | 11% |
| Technical Degree | 9% |
| Other | 8% |

---

**3. Attrition by Age Group**

| Age Group | Employee Count |
| --- | --- |
| 26 – 35 | 585 (Highest) |
| 36 – 45 | 446 |
| 46 – 55 | 221 |
| 18 – 25 | 117 |
| 55+ | 44 |

---

**4. Attrition by Salary Slab**

| Salary Range | Employees |
| --- | --- |
| Up to 5K | 717 (Highest Risk) |
| 5K – 10K | 424 |
| 10K – 15K | 142 |
| 15K+ | 130 |

---

**5. Attrition by Years at Company**

- Highest attrition at **Year 1** with 57 employees leaving — points to onboarding or culture fit issues
- Secondary spikes visible around **Year 5** and **Year 10**

---

**6. Attrition by Job Role**

| Job Role | Count |
| --- | --- |
| Sales Executive | 315 |
| Research Scientist | 275 |
| Laboratory Technician | 248 |
| Sales Representative | 82 |

---

**7. Job Role × Job Satisfaction Matrix**

A cross-tab showing all job roles mapped against satisfaction levels (1 to 4), with total attrition per role visible at a glance.

---

**8. Department Slicer (Interactive Filter)**

Filter the entire dashboard by department — **Human Resources**, **Research & Development**, or **Sales**.

---

## 💡 Key Insights

1. **16.2% overall attrition rate** — 229 out of 1,470 employees left the organization
2. **Low salary is the top driver** — 717 attritions from the under-5K salary bracket
3. **26–35 age group** sees the most attrition — likely due to early career transitions
4. **Year 1 is the most vulnerable** — 57 employees left in their very first year, highlighting onboarding gaps
5. **Sales Executives** have the highest role-wise attrition (315), followed by Research Scientists (275)
6. **Life Sciences graduates** make up 41% of total attrition — the largest education-based segment
7. **Male employees** show higher attrition (136 vs 76) compared to female employees

---

## 🎥 Dashboard Walkthrough

Watch the full dashboard demo here:
[Click to Watch on LinkedIn](your-linkedin-post-link-here)

> Replace the link above after uploading your screen recording to LinkedIn.

---

## 📁 Repository Structure

```
hr-analytics-dashboard/
│
├── Dataset/
│   └── HR_Analytics.csv                   # Raw dataset
│
├── Dashboard/
│   └── HR_Analytics.pbix                  # Power BI project file
│
├── screenshots/
│   └── HR_Analytics_dashboard_img.png     # Dashboard preview image
│
└── README.md                              # Project documentation
```

---

## 🚀 How to Open & Use

1. Clone this repository

```bash
git clone https://github.com/Mahesh-Singh04/hr-analytics-dashboard.git
```

2. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) — it is free

3. Open the file `Dashboard/HR_Analytics.pbix` in Power BI Desktop

4. Use the department slicer to filter views, hover over charts for tooltips, and click visuals to cross-filter

---

## 🙋 About Me

Hi, I am **Mahesh Singh** — an MCA student specializing in Data Analytics, actively looking for fresher Data Analyst opportunities.

This project is part of my portfolio as I build real-world skills and work toward a career in data. I am always learning and genuinely open to feedback!

- LinkedIn: [linkedin.com/in/mahesh-singh04](https://linkedin.com/in/mahesh-singh04)
- GitHub: [github.com/Mahesh-Singh04](https://github.com/Mahesh-Singh04)

---

## 📬 Feedback & Guidance Welcome

I am just getting started on this journey. If you are an experienced Data Analyst or Data Professional, I would genuinely love to hear from you:

- What can I improve in this dashboard?
- What best practices should a fresher focus on?
- Which tools or techniques should I learn next?
- How should I approach practicing to become industry-ready?

Feel free to open an issue, drop a star, or connect with me on LinkedIn. Any comment, suggestion, or guidance means a lot. 🙏

---

*If you found this project helpful or interesting, please consider giving it a star — it really helps!*
