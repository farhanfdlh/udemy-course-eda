# Udemy Course Performance & Pricing Analysis

> Exploratory analysis of 3,678 Udemy courses to understand what drives course popularity, pricing, and revenue — from the platform's perspective — with an interactive Tableau dashboard.

🔴 **[View the interactive dashboard →](https://public.tableau.com/app/profile/farhan.fadhilah.rasyid/viz/UdemyCoursedatasetDataVisualization/Dashboard2)**

---

## 📑 Table of Contents

- [Business Background](#-business-background)
- [Business Objective](#-business-objective)
- [Data Overview](#-data-overview)
- [Approach and Methodology](#-approach-and-methodology)
- [Key Findings](#-key-findings)
- [Business Impact and Recommendations](#-business-impact-and-recommendations)
- [Tools & Tech Stack](#%EF%B8%8F-tools--tech-stack)
- [Author](#-author)

---

## 📌 Business Background

An online course marketplace like Udemy sits between two groups it needs to keep aligned: learners looking for the right course at the right price, and creators deciding what to build and how to price it. Without a clear picture of what's actually driving subscriptions, pricing tolerance, and revenue across the catalog, the platform is left guessing at which subjects to promote, what pricing guidance to give creators, and why growth may be slowing.

## 🎯 Business Objective

From the platform's point of view, this analysis aims to answer:
- Which subjects and courses are driving the most demand, and where is the catalog over- or under-invested?
- What pricing patterns actually correlate with subscriber and revenue outcomes?
- How has course publication and revenue evolved over time — and what does that trend suggest about the platform's growth trajectory?
- What signals (like reviews) are most tied to revenue, and can the platform influence them?

## 📂 Data Overview

| Attribute | Details |
|---|---|
| Source | [Kaggle — Udemy Courses Dataset](https://www.kaggle.com/datasets/refiaozturk/udemy-courses-dataset) |
| Records | 3,678 courses |
| Features | 12 columns: title, subject, price, subscribers, reviews, lectures, level, duration, publish date, paid/free status |

## 🔧 Approach and Methodology

```
Raw Course Dataset (Kaggle)
        ↓
Data Cleaning       → Handle missing/inconsistent values, parse timestamps
        ↓
Exploratory Analysis → Distribution, correlation, and trend analysis (Python)
        ↓
Dashboard Design     → Interactive visualization for stakeholder exploration (Tableau)
```

Analysis was performed across four angles: **popularity** (subscribers, reviews by subject/course), **pricing** (distribution across levels and subjects), **correlation** (price, duration, reviews vs. subscribers), and **time trends** (publication volume and revenue by year).

## 🔍 Key Findings

- **Web Development dominates demand**, accounting for nearly 8 million total subscribers — by far the most popular subject on the platform
- **"Learn HTML5 Programming From Scratch"** is the single most-subscribed course on the platform, with 268,923 subscribers
- **91.57% of courses are paid**, only 8.43% are free — yet free courses attract *more* subscribers and reviews on average than paid ones
- **$20–$25 is the most common price tier**, and course duration and price are positively correlated — longer courses tend to be priced higher
- **Most courses run 1–6 hours**; very few exceed 20 hours of content
- **Course publications peaked in 2016** (1,206 courses published), while **revenue peaked earlier, in 2015 (~$314.5M)**, then declined in subsequent years
- **Number of reviews correlates strongly with revenue** (0.77) — more than most other course attributes, suggesting reviews are a meaningful revenue signal, not just a vanity metric

## 💡 Business Impact and Recommendations

**1. Rebalance catalog investment away from over-concentration in Web Development**
With one subject commanding ~8M of total subscribers, the platform is exposed to concentration risk if demand in that category cools. Recommend actively promoting and incentivizing creator supply in adjacent high-potential but under-represented subjects to diversify the catalog's growth drivers.

**2. Use free courses strategically as a discovery funnel**
Since free courses draw more subscribers and reviews on average, the platform should encourage creators to offer free introductory modules or mini-courses that funnel learners toward paid, deeper content — rather than treating free and paid as fully separate catalogs.

**3. Anchor pricing guidance around the $20–$25 sweet spot**
This is the range where course volume concentrates and price and duration relationships hold consistently. New creators setting prices for standard-length courses should be guided toward this range by default, reserving premium pricing for clearly differentiated, longer-form content.

**4. Investigate the post-2015 revenue decline as a priority, not a footnote**
Publication volume kept growing after 2015, but revenue didn't follow — that gap (more supply, less revenue) points to saturation or pricing pressure and deserves direct investigation (e.g., discounting behavior, increased competition) rather than being read as a simple "more courses, less demand per course" story.

**5. Treat review generation as a revenue lever, not just a trust signal**
Given the strong review-revenue correlation, the platform should consider product nudges that increase review completion rates (e.g., post-completion prompts, incentives) as a direct lever for revenue growth, not only for course credibility.

## 🛠️ Tools & Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Interactive Dashboard | Tableau Public |
| Notebook Environment | Google Colab |
| Data Source | Kaggle |

## 👤 Author

**Farhan Fadhilah Rasyid**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/farhanfdlh)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/farhan-fadhilah-rasyid)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://farhan-portfolio-smoky.vercel.app)

*Co-authored with [Faisal Abu Bakar Riza](https://github.com/FaisalABR).*
