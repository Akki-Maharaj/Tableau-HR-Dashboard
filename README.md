# Tableau HR Analytics Dashboard

> Interactive HR analytics dashboard built with Tableau, tracking 7,984 employees across 7 departments with comprehensive workforce metrics, compensation analysis, and performance insights.

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success)

**Key Metrics:** 7,984 active employees | 89% retention rate | 7 departments | $43K-$93K salary range

---

## 📑 Table of Contents
- [Overview](#-overview)
- [Key Insights](#-key-insights)
- [Recommendations](#-top-recommendations)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Installation](#-getting-started)
- [Usage](#-how-to-use)

---

## 📖 Overview

This dashboard analyzes workforce patterns across 7,984 employees, revealing organizational strengths and improvement areas:

**Workforce Health**: 89% retention rate (8,950 hires, 966 terminations) indicates stability, but Operations shows concerning attrition with 289 exits.

**Pay Equity Challenge**: Gender pay gap of $10K-$15K exists across education levels, requiring immediate attention for legal and ethical compliance.

**Demographic Insights**: Young workforce (70% under 45) creates succession planning needs. Operations dominates at 30% of headcount while HR is critically understaffed.

---

## 🔍 Key Insights

### Workforce & Retention
- **89% retention rate** - above industry average of 85%
- **Operations attrition**: 289 terminations (30% of all exits) - highest risk area
- Consistent hiring growth reaching 8,950 total hires

### Compensation & Equity
- **Salary range**: $43K (entry-level) to $93K (senior management)
- **Gender pay gap**: Males earn $10K-$15K more at same education level
- Compensation by education: PhD ($85K-$93K) | Master's ($65K-$75K) | Bachelor's ($50K-$60K) | High School ($43K-$48K)

### Demographics
- **Gender**: 54% Male, 46% Female (better than 60/40 industry norm)
- **Age**: 25-44 age group dominates | 55+ smallest segment (succession risk)
- **Education**: Bachelor's degree most common | Performance not correlated with education level

### Department Distribution

| Department | Employees | % of Workforce | Key Insight |
|------------|-----------|----------------|-------------|
| Operations | 2,429 | 30% | Highest turnover ⚠️ |
| Sales | 1,634 | 20% | Moderate attrition |
| Customer Service | 1,489 | 19% | High-stress environment |
| IT | 1,243 | 16% | Growing rapidly |
| Marketing | 648 | 8% | Potentially understaffed |
| Finance | 389 | 5% | Small but critical |
| HR | Smallest | <5% | Inadequate for 7,984 employees ⚠️ |

### Performance Distribution
- **Excellent**: 25% | **Good**: 40% | **Satisfactory**: 20% | **Needs Improvement**: 15%

---

## 💡 Top Recommendations

### 🔴 Critical (Immediate - 0-3 months)
1. **Address Operations Attrition** - 289 exits unsustainable
   - Conduct exit interview analysis
   - Review compensation competitiveness and workload
   - Implement retention bonuses

2. **Close Gender Pay Gap** - $10K-$15K disparity across all levels
   - Conduct comprehensive salary equity audit
   - Create compensation adjustment budget
   - Establish transparent pay guidelines

3. **Expand HR Capacity** - Current ratio ~1:250 vs industry standard 1:100
   - Hire 3-5 HR professionals immediately
   - Improve employee support infrastructure

### 🟡 Strategic (3-6 months)
- **Build Leadership Pipeline**: 55+ age group smallest - succession planning critical
- **Performance Development**: Create programs for 15% "Needs Improvement" employees
- **Staffing Review**: Assess Marketing/Finance capacity constraints

---

## 📈 Trends & Risks

### Identified Trends
- Hiring velocity increasing (business growth indicator)
- Age distribution skewing young (70% under 45)
- Operations showing consistent attrition pattern
- Gender balance improving but pay equity lagging

### Risk Matrix

| Risk | Impact | Priority |
|------|--------|----------|
| Operations turnover (289 exits) | High | 🔴 Critical |
| Gender pay gap ($10K-$15K) | High | 🔴 Critical |
| HR understaffing (1:250 ratio) | High | 🔴 Critical |
| Succession gap (few 55+) | Medium | 🟡 Monitor |

---

## 🎨 Features

### Three Interactive Tabs
- **Info** - Navigation guide and dashboard instructions
- **Main Dashboard** - Workforce overview, hiring/termination trends, department breakdown, location map
- **Detailed View** - Demographics, compensation analysis, performance metrics

### Core Capabilities
- **Workforce Tracking**: Active employees, hiring trends, termination analysis
- **Demographics**: Gender, age, education distribution with bubble charts and heat maps
- **Compensation**: Salary analysis by education, gender, age, and role
- **Performance**: Four-level rating system with education correlation
- **Interactive Filtering**: Click-to-filter across all visualizations
- **Export Options**: PDF, PNG, and CSV export capabilities

---

## 📸 Screenshots

### Info Tab
![Information panel with navigation guide and key metrics](screenshots/INFO.png)

### Main Dashboard
![Workforce overview with hiring trends, department breakdown, and location map](screenshots/MAIN.png)

### Detailed View
![Demographics analysis, compensation insights, and performance metrics](screenshots/DETAILS.png)

---

## 🛠️ Built With

- **Tableau Desktop** - Data visualization and interactive dashboard
- **Python Faker** - Synthetic HR data generation
- **Data Modeling** - Star schema with 7+ related tables

---

## 🚀 Getting Started

### Prerequisites
- [Tableau Desktop](https://www.tableau.com/products/desktop/download) (for editing) or Tableau Reader (for viewing)

### Installation

```bash
# Clone repository
git clone https://github.com/Akki-Maharaj/Tableau-HR-Dashboard.git
cd Tableau-HR-Dashboard

# Open .twb or .twbx file in Tableau
# Navigate between Info, Main Dashboard, and Detailed View tabs
```

---

## 💡 How to Use

### Navigation
- Toggle between **Info**, **Main Dashboard**, and **Detailed View** tabs
- Use filter button (top-right) to enable/disable custom filtering

### Interactive Filtering
Click any chart element to cross-filter. Available filters:
- Department | Gender | Education | Age Group | Employment Status | Location

### Export Options
- **PDF Export**: File > Export > PDF (full dashboard or individual sheets)
- **Image Export**: Save visualizations as PNG
- **Data Export**: Extract to Excel/CSV

---

## 📊 Data Source

Uses **synthetic data** (Python Faker library) with realistic HR metrics:
- Employee demographics (gender, age, education)
- Hiring and termination dates
- Department assignments and salaries
- Performance ratings and locations

Ensures **data privacy** while demonstrating real-world HR analytics capabilities.

---

## 🔮 Future Enhancements

- [ ] Predictive attrition modeling for flight risk employees
- [ ] Real-time alerts when turnover exceeds thresholds
- [ ] Compensation benchmarking API integration
- [ ] Skills inventory for internal mobility tracking
- [ ] Mobile-responsive version for executives
- [ ] Integration with HRIS systems

---

## 🤝 Contributing

Contributions welcome! Fork the project, create a feature branch, and submit a pull request.

---

## 👨‍💻 Author

**Akki Maharaj**  
[GitHub](https://github.com/Akki-Maharaj) • [LinkedIn](https://linkedin.com/in/akshat--) • [Email](mailto:akshatg0204@gmail.com)

---

## 🙏 Acknowledgments

- Tutorial: [Data with Baraa](https://www.youtube.com/watch?v=UcGF09Awm4Y)
- Python Faker library for synthetic data
- Tableau community

---

⭐ **Star this repo if helpful!** Perfect for HR professionals, data analysts, and Tableau learners.
