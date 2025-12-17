# 📊 Student Performance Data Analysis

_This project analyzes student exam performance using Python._
_The main goal is to understand how different factors affect student scores in Math, Reading, and Writing._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#Project-Objective">Project Objective</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-conclusion">Conclusion</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

In this project, I studied student performance based on:
- Gender
- Race / Ethnicity
- Parental education level
- Lunch type
- Test preparation course
- I used Python and Plotly to explore the data and create interactive charts.

  ---
<h2><a class="anchor" id="Project-Objective"></a>🎯 Project Objective</h2>
The objectives of this project are:

- To understand how students are distributed by gender and race
- To compare scores between male and female students
- To see how lunch type affects student marks
- To check if test preparation courses help students score better
- To find which subject students struggle with the most

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

**Dataset Used**
- File name: StudentPerformance.csv
- The Data setcontains:
  1. Student Details
  2. Score in subjeects like:- Maths, reading, writing
- Each row represent one student

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python
- Pandas & NumPy – for data handling
- Plotly – for charts and graphs
- Google Colab – for running the code
- GitHub – for sharing the project

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
student-performance-analysis/
│
├── README.md
├── StudentsPerformance.csv
├── Student_Performance_Analysis.ipynb
├── images/
│   └── charts.png

```

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- The data was loaded using Pandas
  - Columns were checked and cleaned
  - New columns were created:
  - Average Score – average of all three subjects
  - Perfect Score – students who scored 100 in any subject
  - Struggling Subject – subject with lowest marks for each student
    
---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Gender Analysis:**
- Counted male and female students
- Compared their scores in all subjects
- Female students scored higher in Reading and Writing
- Male students scored slightly higher in Math

**Race / Ethnicity Analysis:**
- Checked student count in each race group
- Compared gender distribution inside each group

**Parental Education Analysis:**
- Studied how parents’ education affects student performance
- Looked at education levels of female students in Group A

  **Lunch Type Analysis:**
- Compared students with:
1. Standard lunch
2. Free / reduced lunch
- Students with standard lunch scored better on average
- Looked at education levels of female students in Group A

  **Test Preparation Course Analysis:**
- Compared students who completed test preparation
- Students who completed the course scored higher in all subjects

  **Subject Performance:**
- Math was the most difficult subject for many students
- Reading and Writing scores were generally higher
- Total and average scores were compared by gender

 📊**Charts & Visuals:**
- The project includes:
1. Pie charts
2. Bar charts (grouped and stacked)
3. Histogram
4. Scatter plots
5. Box plots
- All charts are interactive and easy to understand.

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

- Open the Googe Colab notebook and run all cells:

---
<h2><a class="anchor" id="final-conclusion"></a>Conclusion</h2>

**This project shows that:**
- Gender, lunch type, and test preparation affect student scores
- Test preparation courses help students improve performance
- Math is the most challenging subject for many students

**This project helped me practice:**
- Data analysis
- Data visualization
- Python programming

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Mukul Dev**  
  Data Analyst  Student(IIT)
🔗 [LinkedIn](https://www.linkedin.com/in/mukul-dev-aa8041394/)
