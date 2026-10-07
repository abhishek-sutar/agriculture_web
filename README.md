# 🇮🇳 India's Agricultural Crop Production Analysis

## 📌 Project Overview

**India's Agricultural Crop Production Analysis** is a data analytics and visualization project developed to analyze agricultural crop production across India.

The project uses an agricultural dataset containing information about **states, districts, crops, agricultural years, seasons, cultivated area, production, production units, and yield**.

The data was prepared and analyzed using **Tableau**, where multiple visualizations were created to identify patterns and relationships in agricultural production.

The project includes an interactive **Tableau Dashboard** and a **Tableau Story**. These analytics were also integrated into a web application using **Python Flask, HTML, and CSS**, making the analysis accessible through a web browser.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze agricultural production and yield patterns across agricultural years.
- Compare cultivated areas across different crops and Indian states.
- Identify states with leading agricultural production.
- Analyze agricultural production across different seasons.
- Understand the distribution of production across different production-unit types.
- Create meaningful and interactive Tableau visualizations.
- Develop an interactive Tableau Dashboard.
- Create a Tableau Story to present the analysis in a structured sequence.
- Integrate the Tableau Dashboard and Story into a web application.
- Provide an accessible browser-based interface for exploring the analysis.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Python** | Backend and web application development |
| **Flask** | Web framework |
| **HTML** | Web page structure |
| **CSS** | Website styling |
| **Tableau** | Data analysis and visualization |
| **Tableau Public** | Dashboard and Story publishing |
| **CSV / Excel** | Data storage and preparation |
| **GitHub** | Version control and project hosting |
| **Vercel** | Web application deployment |

---

## 📂 Project Components

The project consists of the following major components:

1. **Data Collection**
2. **Data Preparation and Preprocessing**
3. **Data Quality Analysis**
4. **Business Question Formulation**
5. **Tableau Visualizations**
6. **Interactive Tableau Dashboard**
7. **Tableau Story**
8. **Flask Web Integration**
9. **HTML and CSS Frontend**
10. **Web Deployment**

---

## 👨‍💻 Project Information

| Detail | Information |
|---|---|
| **Project Name** | India's Agricultural Crop Production Analysis |
| **Student Name** | Abhishek Sutar |
| **Roll No.** | A61 |
| **Department** | AIDS |
| **Project Type** | Data Analytics & Visualization |
| **Date** | 30 September 2026 |

---

# 📊 Dataset

The project uses an agricultural crop production dataset containing information about crop production across different regions of India.

## 📋 Dataset Coverage

| Attribute | Details |
|---|---|
| **Records** | Approximately 345,408 including header |
| **States / UTs** | 36 |
| **Districts** | 729 |
| **Crops** | 57 |
| **Agricultural Years** | 1997-98 to 2020-21 |
| **Seasons** | 6 |
| **Main Measures** | Area, Production, Yield |
| **Production Units** | Tonnes, Bales, Nuts |

---

## 📁 Dataset Fields

The main fields used in the project are:

```text
State
District
Crop
Year
Season
Area
Area Units
Production
Production Units
Yield

```

### Field Description

| Field | Description |
|---|---|
| **State** | Indian state or union territory |
| **District** | District associated with the agricultural record |
| **Crop** | Crop category |
| **Year** | Agricultural year |
| **Season** | Agricultural season |
| **Area** | Cultivated area |
| **Area Units** | Unit used for cultivated area |
| **Production** | Recorded agricultural production |
| **Production Units** | Unit of production such as Tonnes, Bales or Nuts |
| **Yield** | Recorded agricultural yield |

---

# 🧹 Data Preparation and Preprocessing

Before creating the Tableau visualizations, the dataset was inspected and prepared for analysis.

The following preprocessing steps were performed:

- Standardized the `season` field to **Season**.
- Renamed `Production Units.1` to **Yield**.
- Treated **Area, Production and Yield** as numeric measures.
- Treated **State, District, Crop, Season, Area Units and Production Units** as categorical fields.
- Retained **Year** as an agricultural-year label such as `1997-98`.
- Checked the dataset for missing and blank values.
- Checked Area and Production values for negative values.
- Reviewed zero-production records.
- Reviewed potential outlier values before visualization.

### Data Quality Observations

- No blank/null cells were identified in the prepared dataset.
- No negative Area or Production values were identified.
- **1,024 records** had Production equal to zero.
- Zero-production records were retained rather than automatically deleted.
- Some observations contain high values and were retained unless there was a clear reason for removal.

> **Important:** Production is recorded using different units such as **Tonnes, Bales and Nuts**. These units represent different measurements and should not be treated as directly equivalent.

---

# ❓ Business Questions

The Tableau analysis was designed around the following business questions.

### 1. What is the overall agricultural production and yield recorded in the dataset?

**Visualization:** KPI Cards

The dashboard uses KPI cards to provide a quick summary of total recorded production and total yield.

### 2. How does agricultural yield vary across the agricultural years?

**Visualization:** Trend of Agricultural Yield — Line Chart

This visualization shows how recorded agricultural yield changes across the agricultural years.

### 3. How is agricultural production distributed across Indian states?

**Visualization:** State-wise Agricultural Production — India Map

The map provides a geographic view of agricultural production across Indian states.

### 4. Which crops occupy the largest cultivated areas?

**Visualization:** Comparison of Cultivated Area by Crop — Horizontal Bar Chart

The horizontal bar chart compares cultivated area across different crops.

### 5. How does cultivated area vary among Indian states?

**Visualization:** State-wise Cultivated Area — Treemap / Bar View

This visualization compares the cultivated area associated with different Indian states.

### 6. Which Indian states are the leading agricultural producers?

**Visualization:** Leading States by Agricultural Production — Packed Bubble Chart

The packed bubble chart provides a visual comparison of agricultural production across states.

### 7. How does total agricultural production change across agricultural years?

**Visualization:** Year-wise Total Agricultural Production — Line Chart

The line chart presents the recorded production trend from agricultural year 1997-98 through 2020-21.

### 8. How is agricultural production distributed across seasons and production-unit types?

**Visualization:** Season-wise Agricultural Production Share and Production Distribution by Unit Type — Pie Charts

These visualizations show the distribution of recorded production across agricultural seasons and production-unit categories.

---

# 📈 Tableau Visualizations

The project contains the following major Tableau visualizations:

| # | Visualization | Chart Type | Purpose |
|---|---|---|---|
| 1 | **Total Production** | KPI Card | Shows total recorded production |
| 2 | **Total Yield** | KPI Card | Shows total recorded yield |
| 3 | **Trend of Agricultural Yield** | Line Chart | Shows year-wise yield trend |
| 4 | **State-wise Agricultural Production** | India Map | Shows geographic production distribution |
| 5 | **Comparison of Cultivated Area by Crop** | Horizontal Bar Chart | Compares cultivated area by crop |
| 6 | **State-wise Cultivated Area** | Treemap / Bar Chart | Compares cultivated area by state |
| 7 | **Leading States by Agricultural Production** | Packed Bubble Chart | Compares production across states |
| 8 | **Year-wise Total Agricultural Production** | Line Chart | Shows production across agricultural years |
| 9 | **Production Distribution by Unit Type** | Pie Chart | Shows distribution by production unit |
| 10 | **Season-wise Agricultural Production Share** | Pie Chart | Shows production distribution by season |

---

# 📌 Key Dashboard Values

The final Tableau Dashboard displays:

- **Total Yield:** 27.43M
- **Total Production:** 330,997.84M units

These values represent the aggregations displayed by the Tableau Dashboard for the prepared dataset.

---

# 🔎 Data Interpretation Note

The agricultural year in this project is represented using labels such as:

```text
1997-98
1998-99
...
2020-21

```

---

# 📊 Tableau Dashboard

The project includes an interactive Tableau Dashboard titled:

**India's Agricultural Crop Production Analysis**

The dashboard combines multiple visualizations into a single analytical interface to provide an overview of agricultural production across India.

## Dashboard Components

- **State-wise Agricultural Production** — India Map
- **State-wise Cultivated Area** — Bar Chart
- **Leading States by Agricultural Production** — Packed Bubble Chart
- **Total Yield** — KPI Card
- **Total Production** — KPI Card
- **Agricultural Production** — Pie Chart
- **Production Distribution by Unit Type** — Pie Chart
- **Year-wise Total Agricultural Production** — Line Chart
- **Trend of Agricultural Yield** — Line Chart
- **State-wise Cultivated Area Comparison** — Treemap

## Key Dashboard Values

| KPI | Value |
|---|---|
| **Total Yield** | 27.43M |
| **Total Production** | 330,997.84M units |

---

# 📖 Tableau Story

A Tableau Story was created to present the agricultural analysis in a structured sequence.

The Story contains **8 Story Points**:

1. **Agricultural Performance**
2. **Geographic Distribution**
3. **Cultivated Area Across Indian States**
4. **Leading States by Agricultural Production**
5. **Year-wise Agricultural Production**
6. **Trend of Agricultural Yield**
7. **Season-wise Agricultural Production**
8. **Production Distribution by Unit Type**

The Story allows users to move through the different analytical views and understand the agricultural production analysis step by step.

---

# 🌐 Web Integration

The Tableau Dashboard and Story were integrated into a web application using **Python Flask, HTML and CSS**.

The purpose of the web integration is to provide users with a simple web interface through which they can access the Tableau analytics.

## Web Integration Technologies

- **Python**
- **Flask**
- **HTML5**
- **CSS3**
- **Tableau Public**

---

# 🐍 Flask Application

Flask is used as the backend framework for handling the different pages of the web application.

The application contains the following routes:

```text
/
 /dashboard
 /story

 ```

## Route Description

| Route | Purpose |
|---|---|
| `/` | Opens the project homepage |
| `/dashboard` | Opens the Tableau Dashboard page |
| `/story` | Opens the Tableau Story page |

### Example Flask Routing

```python
@app.route("/")
def home():
    return render_template("index.html")

@app.route("/dashboard")
def dashboard():
    return render_template("dashboard.html")

@app.route("/story")
def story():
    return render_template("story.html")
```

    ---

# 📁 Project Structure

The GitHub repository contains the main web application files and deployment configuration.

```text
agriculture_web/
│
├── Static/
│   └── style.css
│
├── Templates/
│   ├── index.html
│   ├── dashboard.html
│   └── story.html
│
├── api/
│
├── app.py
├── requirements.txt
├── vercel.json
├── .gitignore
└── .vercelignore

```
---

## Folder and File Description

| File / Folder | Purpose |
|---|---|
| **Static/** | Contains CSS and other static resources |
| **Templates/** | Contains HTML templates for the web pages |
| **api/** | Contains deployment/API-related files |
| **app.py** | Main Flask application file |
| **requirements.txt** | Contains the required Python dependencies |
| **vercel.json** | Contains Vercel deployment configuration |
| **.gitignore** | Specifies files ignored by Git |
| **.vercelignore** | Specifies files ignored during Vercel deployment |

---

# 🎨 Frontend

The frontend of the web application is developed using **HTML5 and CSS3**.

## HTML

HTML is used to create:

- Project homepage
- Navigation menu
- Dashboard page
- Story page
- Buttons and links
- Content sections
- Tableau embedding sections

## CSS

CSS is used for:

- Website layout
- Navigation styling
- Buttons
- Cards
- Typography
- Spacing
- Responsive design
- Overall visual appearance

The CSS file is stored inside the `Static` folder.

---

# ▶️ How to Run the Project Locally

## 1. Clone the Repository

```bash
git clone https://github.com/abhishek-sutar/agriculture_web.git

```

## 2. Open the Project Folder

```bash
cd agriculture_web

```

## 3. Install Required Dependencies

```bash
pip install -r requirements.txt

```

## 4. Run the Flask Application

```bash
python app.py

```

## 5. Open the Website

After the Flask application starts successfully, open the following address in your web browser:

```text
http://127.0.0.1:5000/

```

---

# 🔗 Project Links

## 🌐 Deployed Web Application

[Open Agriculture Web Application](https://agriculture-web-pi.vercel.app/)

## 📊 Tableau Dashboard

[View Tableau Dashboard](https://public.tableau.com/views/IndiasCropProductionAnalysisdashboard/AgriculaturalProductionDashboard)

## 📖 Tableau Story

[View Tableau Story](https://public.tableau.com/app/profile/prarthana.akhare/viz/Indiascropproductionanalysisstory/IndiasCropProductionAnalysisstory)

## 💻 GitHub Repository

[View GitHub Repository](https://github.com/abhishek-sutar/agriculture_web)

---

---

# ⚡ Performance Testing

The web application was tested to ensure that the main pages and Tableau integrations work correctly.

| Test | Result |
|---|---|
| Homepage Loading | Successful |
| Dashboard Page | Successful |
| Story Page | Successful |
| Flask Application | Successful |
| Tableau Dashboard Integration | Successful |
| Tableau Story Integration | Successful |
| Localhost Testing | Successful |
| Vercel Deployment | Successful |
| GitHub Repository | Successfully maintained |

The application was tested locally using Flask and was also deployed online using Vercel.

---

# 🚀 Future Scope

The project can be further improved by adding the following features:

- Add more recent agricultural data.
- Add additional crop-level analysis.
- Include crop price and market-value information.
- Add rainfall and weather-related datasets.
- Include fertilizer and irrigation information.
- Add advanced filters for crops, states, seasons, and years.
- Improve the interactive web interface.
- Add user authentication if required.
- Add automated data updates.
- Develop predictive models for future agricultural production.
- Deploy an interactive analytics system with regularly updated data.

---

# 🎯 Conclusion

The **India's Agricultural Crop Production Analysis** project provides a comprehensive visualization-based analysis of agricultural production across India.

Using **Tableau**, the project analyzes production, yield, cultivated area, states, crops, agricultural years, seasons, and production-unit types through interactive visualizations.

The Tableau Dashboard provides a consolidated view of important agricultural insights, while the Tableau Story presents the analysis in a structured sequence.

The integration of Tableau with **Python Flask, HTML, and CSS** makes the analysis accessible through a web application. The project was also deployed using **Vercel**, providing an online interface for accessing the analytics.

Overall, the project demonstrates the practical use of **data preparation, data visualization, business-question formulation, Tableau analytics, web integration, and deployment** in an agricultural data analysis project.

---

# 👨‍💻 Author

**Abhishek Sutar**

**Roll No.: A61**  
**Department: AIDS**

### Technologies Used

- Python
- Flask
- HTML5
- CSS3
- Tableau
- Tableau Public
- GitHub
- Vercel

---

# ⭐ Project Summary

**India's Agricultural Crop Production Analysis** combines data analytics and web technologies to transform agricultural data into meaningful and interactive insights.

The complete project includes:

**Dataset → Data Preparation → Business Questions → Tableau Visualizations → Dashboard → Story → Flask Web Integration → Deployment**

---

---

# 📚 Project Documentation

The project documentation includes the following supporting materials:

- 📌 Problem Statement
- 💡 Brainstorming and Idea Prioritization
- 🧠 Empathy Map
- 📊 Dashboard Design
- 📖 Tableau Story Design
- 📄 Final Project Report
- 📁 Dataset
- 🌐 Web Integration
- 📸 Project Screenshots

These documents provide detailed information about the project development process, data analysis, visualization design, Tableau implementation, and web integration.

---

# 📌 Final Project Overview

| Component | Technology / Tool |
|---|---|
| **Dataset** | CSV / Excel |
| **Data Analysis** | Tableau |
| **Dashboard** | Tableau |
| **Story** | Tableau |
| **Web Backend** | Python Flask |
| **Frontend** | HTML5 & CSS3 |
| **Version Control** | GitHub |
| **Deployment** | Vercel |

---

# 🏁 End of Project

Thank you for exploring **India's Agricultural Crop Production Analysis**.

The project demonstrates how agricultural data can be transformed into meaningful insights using data analytics, visualization, and web technologies.

---
