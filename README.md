# Zomato India Market Analysis

### End-to-End Data Analytics Project
## Restaurant Market Intelligence & Competitive Benchmarking

**Project Status:** Planning & Scope Definition

**Tools:** Python | SQL | Google BigQuery | Tableau | GitHub

## 1. Project Overview

This project aims to analyze restaurant ratings and customer review engagement in India using the Zomato dataset.

The analysis will explore relationships between restaurant ratings, pricing categories, geographic locations, and service availability to identify patterns that may support competitive positioning and business decision-making.

## 2. Business Problem

Restaurants operate in competitive markets where understanding customer ratings and market characteristics can support strategic decisions.

However, identifying patterns associated with higher restaurant ratings requires evaluating multiple factors, including pricing, available services, and geographic location.

This project seeks to provide data-driven insights into these relationships using the available Zomato restaurant data.

## 3. Project Objectives

### General Objective

Analyze the ratings and vote volume of restaurants listed in the Zomato dataset for India, evaluating variations based on price ranges, available services, and geographic location, with the aim of identifying patterns in reputation and engagement that will facilitate comparisons across market segments and help prioritize areas for future research and improvement initiatives.
>We have restaurants across various cities, price segments, and types. We want to understand which ones have the best and worst reputation metrics, in order to identify where we should focus our efforts on improvement and support for these restaurants.

### Specific Objectives

**Objective 1 - Service Availability**

Compare restaurant ratings based on the availability of online delivery and table booking services to identify potential differences between restaurants offering these services and those that do not.

> To help restaurants decide where to conduct research and invest resources to improve the customer experience.

**Objective 2 - Pricing Analysis**

Analyze the relationship between restaurant price ranges and customer ratings to identify potential patterns of association.

>To help restaurants understand how they are positioned relative to other establishments in the same price segment, and how they can become more competitive within that segment.

**Objective 3 - Geographic Analysis**

Analyze and compare restaurant ratings and voting volumes across different Indian cities to identify geographic patterns in restaurant reputation and customer review engagement.
>So that Zomato can identify markets where it would be advisable to conduct further research or prioritize commercial initiatives.

## 4. Dataset Information

**Source:** [Zomato Market Analysis - Kaggle](https://www.kaggle.com/datasets/srisyra02/zomato-market-analysis)

The original dataset contains 9,551 restaurant records across multiple countries.

This project focuses on the 8,652 records associated with India.

### Main Variables

- Restaurant Name
- Country Code
- City
- Aggregate rating
- Votes
- Price range
- Average Cost for two
- Has Online delivery
- Has Table booking

### Initial Considerations

- The analysis focuses exclusively on restaurants located in India.
- Cities with limited restaurant records will be evaluated carefully before inclusion in comparative rankings.
- Unrated restaurants will be handled separately from restaurants with valid ratings.
- Customer votes will be treated as an indicator of review engagement, not as a direct measure of sales or customer volume.
- The dataset does not support temporal trend analysis or causal conclusions.

## 5. Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas) | Data inspection, cleaning, and preparation |
| Google Colab | Python development environment |
| Google BigQuery | Data storage and SQL analysis |
| SQL | Data querying and aggregation |
| Tableau | Interactive dashboards and data visualization |
| GitHub | Version control and project documentation |

## 6. Project Workflow

The project is planned around five main activities:

1. Data Selection & Initial Assessment
2. Data Cleaning & Preparation
3. Exploratory Data Analysis (EDA)
4. Data Visualization & Dashboard Development
5. Insights & Business Recommendations

## 7. Project Scope

The analysis will focus on restaurant records from India.

The main analytical dimensions include:

- Customer ratings
- Customer review engagement
- Restaurant pricing
- Online delivery availability
- Table booking availability
- Geographic differences between cities

### Out of Scope

- Restaurants located outside India
- Sales, revenue, and profitability analysis
- Individual customer behavior
- Historical or time-series analysis
- Causal inference
- Cuisine-type comparisons as a primary analytical objective

## 8. Project Deliverables

The planned deliverables include:

- Cleaned restaurant dataset
- Data quality documentation
- Exploratory data analysis notebook
- Interactive Tableau dashboard
- Final insights and business recommendations

## 9. Project Progress

**Current Phase:** Project Planning

- [x] Define the business problem
- [x] Establish the general objective
- [x] Define specific objectives
- [x] Select the geographic scope
- [x] Define initial data assessment activities
- [x] Define data cleaning activities
- [ ] Finalize the Statement of Work
- [ ] Perform data cleaning
- [ ] Conduct exploratory data analysis
- [ ] Develop SQL queries
- [ ] Build Tableau dashboard
- [ ] Document findings and recommendations

## 10. Data Source & Acknowledgment

Dataset provided through Kaggle:

[Zomato Market Analysis](https://www.kaggle.com/datasets/srisyra02/zomato-market-analysis)

This project is developed for educational and portfolio purposes.

All analytical findings will be based on the available dataset and its documented limitations.
