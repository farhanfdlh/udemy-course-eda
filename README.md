# 📊 Udemy Course Data Analytics — Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-E97627?logo=tableau)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

> A practical data analytics module using the Udemy Courses Dataset as a case study. This project explores course trends, pricing, subscriber behavior, and revenue insights through EDA and interactive Tableau dashboards.

---

## 📌 Project Overview

This project uses a dataset of 3,678 Udemy courses to perform a full Exploratory Data Analysis (EDA) and data visualization.

### Problem Statement
Understanding what factors drive course popularity, pricing strategy, and revenue on the Udemy platform — from both a learner's and a course creator's perspective.

### Goals
- Identify the most popular courses and subjects by subscriber count
- Analyze price and duration distributions across course levels and subjects
- Explore correlations between price, duration, reviews, and subscriber count
- Track publication trends by year and month
- Evaluate annual revenue patterns

---

## 📂 Dataset

| Property | Details |
|---|---|
| **Source** | [Kaggle — Udemy Courses Dataset](https://www.kaggle.com/datasets/refiaozturk/udemy-courses-dataset) |
| **Records** | 3,678 courses |
| **Features** | 12 columns |

### Column Descriptions

| Column | Description |
|---|---|
| `course_id` | Unique identifier for each course |
| `course_title` | Title of the course |
| `url` | Direct link to the course on Udemy |
| `is_paid` | Whether the course is paid (`True`) or free (`False`) |
| `price` | Course price in USD |
| `num_subscribers` | Total number of enrolled students |
| `num_reviews` | Total number of reviews |
| `num_lectures` | Total number of lectures |
| `level` | Difficulty level (Beginner, Intermediate, Expert, All Levels) |
| `content_duration` | Total content duration in hours |
| `published_timestamp` | Date and time the course was first published |
| `subject` | Main subject category (Web Development, Business Finance, etc.) |

---

## 🔍 Key Findings

- **Web Development** dominates with nearly **8 million total subscribers** — the most popular subject on Udemy
- **"Learn HTML5 Programming From Scratch"** is the single most subscribed course with **268,923 subscribers**
- **91.57%** of all courses on Udemy are paid; only 8.43% are free
- Free courses attract **more subscribers and reviews** than paid courses on average
- Courses priced around **$20–$25** are the most common price tier
- Most courses have a duration of **1–6 hours**; very few exceed 20 hours
- Course duration and price show a **positive correlation** — longer courses tend to cost more
- Udemy saw its **peak course publications in 2016** (1,206 courses published)
- Revenue peaked in **2015 at ~$314.5M**, followed by a decline in subsequent years
- `num_reviews` and `revenue` have a strong positive correlation (**0.77**), suggesting that highly reviewed courses generate more income

---

## 🛠️ Built With

| Category | Tools |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Interactive Dashboard | Tableau Public |
| Notebook Environment | Google Colab |
| Data Storage | Google Drive, CSV |
| Dataset Source | Kaggle |

---

## 📊 Tableau Dashboard

Explore the interactive dashboard here:

🔗 **[Udemy Course Dataset — Data Visualization (Tableau Public)](https://public.tableau.com/views/UdemyCoursedatasetDataVisualization/DashboardVisualisasiDataUdemyCourse)**

The dashboard includes:
- Top 10 courses by various metrics (subscribers, revenue, lectures, etc.)
- Free vs. Paid course distribution
- Average metrics by subject, level, and paid status
- Course publication trends by year and month
- Annual revenue and subscriber trends

---

## 👥 Authors

| Name | GitHub |
|---|---|
| Faisal Abu Bakar Riza | [@FaisalABR](https://github.com/FaisalABR) |
| Farhan Fadhilah Rasyid | [@farhanfdlh](https://github.com/farhanfdlh) |

---

## 📄 License

This project is licensed under the [MIT License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---
