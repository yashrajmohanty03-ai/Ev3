# 📈 Google Play Store Install Trend Analysis Dashboard

> A Data Analytics and Visualization project that analyzes historical app installation trends across Google Play Store categories and highlights significant month-over-month growth using Python and Matplotlib.

---

# 📑 Table of Contents

- <a href="#project-title">Project Title</a>
- <a href="#brief-summary">Brief One Line Summary</a>
- <a href="#overview">Overview</a>
- <a href="#problem-statement">Problem Statement</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools-and-technologies">Tools and Technologies</a>
- <a href="#methods">Methods</a>
- <a href="#key-insights">Key Insights</a>
- <a href="#dashboard-model-output">Dashboard / Output</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#how-to-run-this-project">How to Run this Project?</a>
- <a href="#results-conclusion">Results & Conclusion</a>
- <a href="#future-work">Future Work</a>
- <a href="#author-contact">Author & Contact</a>

---

<h2 id="project-title">📌 Project Title</h2>

# Google Play Store Install Trend Analysis Dashboard

---

<h2 id="brief-summary">📝 Brief One Line Summary</h2>

A Python-based analytics dashboard that generates historical installation trends, identifies significant growth periods, and visualizes category-wise app adoption using Matplotlib.

---

<h2 id="overview">📖 Overview</h2>

This project analyzes Google Play Store application data to study installation growth patterns across different app categories over time.

The system creates historical installation records, applies category-based business filters, identifies high-growth periods, and visualizes trends through line charts with highlighted growth regions.

The project demonstrates how data analytics and visualization techniques can be used to uncover category-level growth patterns and user adoption trends.

---

<h2 id="problem-statement">⚠️ Problem Statement</h2>

Analyzing app growth trends manually across thousands of applications is difficult and time-consuming.

This project aims to:

- Analyze installation growth across app categories
- Generate historical installation trends
- Identify significant growth periods
- Visualize category-wise performance
- Discover emerging market opportunities
- Support data-driven decision making

---

<h2 id="dataset">📂 Dataset</h2>

The project uses a Google Play Store dataset containing application information.

### Dataset Features

- App Name
- Category
- Installs
- Reviews
- Rating
- Size
- Price
- Content Rating

### Data Processing

The project performs:

- Install count cleaning
- Review count cleaning
- Missing value removal
- Historical data generation
- Category filtering
- Monthly trend aggregation

---

<h2 id="tools-and-technologies">🛠️ Tools and Technologies</h2>

## Programming Language

- Python

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- ZoneInfo
- Datetime

## Development Environment

- Jupyter Notebook
- VS Code

---

<h2 id="methods">⚙️ Methods</h2>

## 1. Data Cleaning

The following preprocessing steps were applied:

- Install count cleaning
- Review count conversion
- Missing value handling
- Invalid row removal

---

## 2. Historical Data Generation

To simulate app growth patterns:

- Monthly data was generated for 24 months
- Growth rates were randomly applied
- Install counts were incrementally increased
- Historical installation records were created

---

## 3. Data Filtering

The following business rules were applied:

### Review Filter

```text
Reviews > 500
```

### App Name Filter

Removed applications starting with:

```text
X, Y, Z
```

Removed applications containing:

```text
s / S
```

### Category Filter

Only categories beginning with:

```text
B, C, E
```

were retained.

---

## 4. Category Translation

Categories were translated into multiple languages for visualization:

| Original Category | Display Category |
|------------------|------------------|
| Beauty | सौंदर्य |
| Business | வணிகம் |
| Dating | Partnersuche |

---

## 5. Monthly Trend Analysis

The project calculates:

- Monthly installs
- Category-wise installs
- Month-over-month growth rates
- Significant growth indicators

---

## 6. Growth Detection

A category is marked as significant when:

```text
Month-over-Month Growth > 20%
```

---

<h2 id="key-insights">📊 Key Insights</h2>

- Certain categories consistently outperform others in installation growth.
- High review counts are strongly associated with installation growth.
- Month-over-month analysis helps identify emerging categories.
- Significant growth periods become easier to identify through visualization.
- Category-level analytics provides better market understanding.

---

<h2 id="dashboard-model-output">📈 Dashboard / Output</h2>

## Dashboard Workflow

```text
Google Play Store Dataset
          ↓
Data Cleaning
          ↓
Historical Data Generation
          ↓
Business Rule Filtering
          ↓
Category Translation
          ↓
Monthly Aggregation
          ↓
Growth Detection
          ↓
Trend Visualization
```

---

## 📊 Line Chart Visualization

The dashboard visualizes:

- Monthly installs by category
- Growth patterns over time
- Significant growth regions
- Comparative category performance

### Highlighted Regions

Areas with:

```text
Growth > 20%
```

are highlighted automatically.

---

## ⏰ Time-Based Dashboard Access

The dashboard includes configurable time restrictions using:

```python
ZoneInfo("Asia/Kolkata")
```

allowing dashboard visibility during specific business hours.

---

<h2 id="project-structure">📁 Project Structure</h2>

```bash
Google_Play_Store_Trend_Analysis/

│
├── task3.ipynb
├── google_play_store_dataset.csv
├── README.md
└── outputs/
```

---

<h2 id="how-to-run-this-project">🚀 How to Run this Project?</h2>

## Clone Repository

```bash
git clone https://github.com/yashrajmohanty03-ai/google-play-store-trend-analysis.git

cd google-play-store-trend-analysis
```

## Install Dependencies

```bash
pip install pandas numpy matplotlib
```

## Run Notebook

```bash
jupyter notebook task3.ipynb
```

## Execute All Cells

Run all notebook cells sequentially to:

- Load dataset
- Clean installation data
- Generate historical trends
- Apply category filters
- Calculate growth rates
- Visualize installation trends

---

<h2 id="results-conclusion">📈 Results & Conclusion</h2>

## Results

The project successfully:

- Generated 24 months of historical installation data
- Identified category-wise growth patterns
- Detected significant month-over-month growth
- Created interactive trend visualizations
- Highlighted high-growth periods automatically

---
## Output
! [image alt](https://github.com/yashrajmohanty03-ai/Ev3/blob/bcc2cdf28a9e4fc58471aec8f7077e06edff9dde/output.png)

## Conclusion

This project demonstrates how data analytics and visualization can be used to understand application growth patterns in the Google Play Store ecosystem. Through historical trend generation, category filtering, and growth analysis, valuable insights can be extracted to support business intelligence and market research activities.

---

<h2 id="future-work">🔮 Future Work</h2>

Future enhancements include:

- Interactive Plotly dashboards
- Streamlit deployment
- Real-time Google Play Store integration
- Predictive install forecasting
- Machine Learning-based trend prediction
- Advanced category comparison analytics
- Automated reporting system

---

<h2 id="author-contact">👨‍💻 Author & Contact</h2>

## Yashraj Mohanty

### Areas of Interest

- Data Analytics
- Data Visualization
- Business Intelligence
- Machine Learning

### Contact

- GitHub: https://github.com/yashrajmohanty03-ai
- LinkedIn: https:// linkedin.com/in/yashraj-mohanty
- Email: yashrajmohanty3@gmail.com

---

<p align="center">
⭐ If you found this project useful, consider giving it a star on GitHub!
</p>
