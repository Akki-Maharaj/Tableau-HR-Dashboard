# Human Resources Dashboard

A comprehensive, interactive HR analytics dashboard built with **Tableau** for visualizing and analyzing workforce data, employee demographics, compensation trends, and departmental performance. This dashboard provides actionable insights for HR professionals and management through intuitive visualizations and interactive filtering.

## 🎯 Features

- **Multi-Tab Interface**: Three dedicated views (Info, Main Dashboard, Detailed View)
- **Workforce Overview**: Track active employees, hiring trends, and termination rates
- **Demographics Analysis**: Visualize employee distribution by gender, age, and education level
- **Department Insights**: Monitor headcount and performance across all departments
- **Compensation Analytics**: Analyze salary trends by education, gender, age, and role
- **Performance Metrics**: Evaluate employee performance across education levels
- **Geographic Distribution**: View employee location data with interactive maps
- **Custom Filters**: Dynamic filtering to drill down into specific data segments
- **Export Capabilities**: Download reports and visualizations in PDF format
- **Interactive Visualizations**: Click-to-filter functionality across all charts

## 📸 Screenshots

### Info Tab
![Dashboard Info](./screenshots/INFO.png)
*Information panel with navigation and key instructions*

### Main Dashboard
![Main Dashboard](./screenshots/MAIN.png)
*Overview panel showing active employees (7,984), hiring trends (8,950), termination data (966), department breakdown, and location distribution*

### Detailed View
![Detailed View](./screenshots/DETAILS.png)
*Demographics analysis, income insights, and performance metrics with interactive visualizations*

## 🛠️ Built With

- **Tableau** - Primary data visualization and dashboard tool
- **Python Faker Library** - Synthetic HR data generation for demonstration purposes
- **Data Source**: Custom-generated employee dataset with realistic HR metrics

## 📊 Dashboard Structure

### Info Tab
- Dashboard navigation guide
- Key metrics legend
- Filter instructions
- Quick reference for dashboard features

### Main Dashboard (Overview)
- **Active Employees**: 7,984 total workforce
- **Hiring Trends**: Line chart showing 8,950 total hires over time
- **Termination Analysis**: 966 terminations tracked with trend line
- **Departments**: Horizontal bar chart with breakdown:
  - Operations: 2,429 employees (289 terminated)
  - Sales: 1,634 employees
  - Customer Service: 1,489 employees
  - IT: 1,243 employees
  - Marketing: 648 employees
  - Finance: 389 employees
  - HR: Smallest department
- **Location Map**: Geographic distribution (HQ vs Branch locations)

### Detailed View (Demographics & Income)
- **Gender Distribution**: Donut charts showing Male (54%, 89%) and Female (46%, 11%) breakdown
- **Education & Age Matrix**: Bubble chart showing distribution across:
  - Education levels: H-Sch, Bachelor, Master, PhD
  - Age groups: >25, 25-34, 35-44, 45-54, 55+
- **Education & Performance**: Heat map showing performance ratings (Excellent, Good, Satisfactory, Needs Improvement) by education level
- **Education & Gender Income**: Horizontal bar charts comparing salaries (43K-93K range) by education and gender
- **Age & Salary**: Scatter plot showing salary distribution by age and role:
  - Finance Manager
  - IT Manager
  - Operations Manager
  - Sales Consultant
  - Financial Analyst
  - Sales Specialist
  - HR Manager
  - HR Assistant

## 🚀 Getting Started

### Prerequisites

- **Tableau Desktop** (for editing) or **Tableau Reader** (for viewing)
- Download from: [Tableau Downloads](https://www.tableau.com/products/desktop/download)

### Installation & Usage

1. Clone the repository
```bash
git clone https://github.com/yourusername/hr-dashboard-tableau.git
cd hr-dashboard-tableau
```

2. Open the Tableau workbook
```bash
# Double-click the .twb or .twbx file
# Or open Tableau and select File > Open
```

3. Explore the dashboard
   - Navigate between Info, Main Dashboard, and Detailed View tabs
   - Use the Filter toggle (top-right) to enable custom filtering
   - Click on any chart element to filter related visualizations
   - Export views using File > Export > PDF

## 🎨 Interactive Features

### Custom Filters
- Toggle filters ON/OFF using the filter button (top-right)
- Click on chart elements to cross-filter data
- Filter by:
  - Department
  - Gender
  - Education level
  - Age group
  - Employment status (Hired/Terminated)
  - Location

### Export Options
- **PDF Export**: Download complete dashboard or individual sheets
- **Image Export**: Save visualizations as PNG files
- **Data Export**: Extract underlying data to Excel/CSV

## 📈 Key Metrics Tracked

- **Workforce**: 7,984 active employees
- **Hiring**: 8,950 total hires with trend analysis
- **Attrition**: 966 terminations tracked
- **Demographics**: Gender, age, and education distribution
- **Departments**: 7 major departments with headcount
- **Compensation**: Salary ranges from 43K to 93K across roles
- **Performance**: Four-level rating system (Excellent to Needs Improvement)
- **Geography**: Multi-location tracking (HQ and Branch offices)

## 📚 Data Source

The dashboard uses **synthetic data** generated using Python's **Faker library**, creating realistic HR records including:
- Employee demographics
- Hiring and termination dates
- Department assignments
- Salary information
- Performance ratings
- Location data

This approach ensures data privacy while providing a realistic demonstration of HR analytics capabilities.

## 🎓 Learning Resource

This dashboard was created following the tutorial:
**[YouTube Tutorial Link](https://www.youtube.com/watch?v=UcGF09Awm4Y&t=11106s)** *(timestamp: 3:05:06)*

Credit to the original tutorial creator for the excellent guidance on Tableau dashboard development.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/Enhancement`)
3. Commit your Changes (`git commit -m 'Add some Enhancement'`)
4. Push to the Branch (`git push origin feature/Enhancement`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/Akki-Maharaj)
- LinkedIn: [Your Name](https://linkedin.com/in/akshat--)

## 🙏 Acknowledgments

- Tutorial by [Data with baraa] - [YouTube Channel](https://www.youtube.com/watch?v=UcGF09Awm4Y)
- Python Faker library for synthetic data generation
- Tableau community for best practices and inspiration

## 📧 Support

For questions or support:
- Open an issue on GitHub
- Connect via LinkedIn
- Email: akshatg0204@gmail.com

---

⭐ **If you find this project helpful, please give it a star!**

💼 **Perfect for**: HR professionals, data analysts, Tableau learners, and anyone interested in workforce analytics
