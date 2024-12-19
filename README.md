# Vanguard UI A/B Test Analysis

## Introduction

This repository contains the analysis and deliverables for the Module 2 project of the Ironhack Data Analytics Bootcamp: evaluating Vanguard’s new digital user interface (UI) through an A/B test. The project focuses on Exploratory Data Analysis (EDA), performance metrics evaluation, hypothesis testing, and data visualization to assess the experiment's results.

## Project Context

### Objective

Vanguard conducted an A/B test from March to June 2017 to assess whether a redesigned digital interface with intuitive prompts improved the process completion rate compared to the traditional interface.

- **Control Group:** Clients using the traditional interface.
- **Test Group:** Clients using the redesigned interface.

### Goals

- Evaluate completion rates, time spent on each step, error rates, and overall completion times.
- Analyze client profiles considering key demographic factors such as gender, age, tenure, and balance.
- Perform hypothesis testing to validate the significance of results.
- Create interactive visualizations in Tableau for stakeholder presentation.
  
---

## Datasets

The analysis uses three main datasets:

1. **Client Profiles (df_final_demo):** Demographic data of clients (age, gender, tenure, balance).
2. **Digital Footprints (df_final_web_data):** A detailed trace of client interactions online.
3. **Experiment Roster (df_final_experiment_clients):** A list revealing which clients were part of the experiment and the group they were assigned to.

---

## Methodology

### Performance Metrics

- **Completion Rate:** Proportion of users who completed the process.
- **Error Rates:** Frequency of users returning to a previous step.
- **Time per Step:** Average time spent on each process step.
- **Total Completion Time:** Total time taken to complete the entire process.

### Hypothesis Testing

- Statistical tests for completion rates, error rates, and total time between the Test and Control groups.
- Cost-effectiveness test to verify a 5% increase in completion rates.

### Demographic Analysis

- We analyzed the client profiles, considering key demographic factors like gender, age, tenure, and balance, to ensure there were no biases between the groups.

### Visualizations

Results were exported to CSV files for Tableau visualization, including KPI comparisons and demographic insights.

---

### Key Findings

- The new UI increased completion rates by more than 5%, meeting the cost-effectiveness threshold.
- There were more errors in the Test group compared to the Control group. We rejected the null hypothesis, indicating a significant difference in error rates between the groups.
- The average completion time was longer for the Test group, but we could not reject the null hypothesis for total time, meaning there was no significant difference in completion times between the groups.
- The demographic analysis of client profiles (gender, age, tenure, balance) showed no significant biases between the Test and Control groups, confirming the experimental design was balanced.

---

## Deliverables

1. **Jupyter Notebook:** Code for data cleaning and analysis.
2. **.py Files:** Functions used in the analysis.
3. **Tableau Dashboards:** Interactive visualizations.
4. **README:** Project documentation.
5. **Presentation:** Slides summarizing findings and recommendations.

---

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vanguard-ab-test.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to view the analysis and generate CSV files.
4. Open Tableau to explore the dashboards.

---

## Links

- **GitHub Repository:** [Vanguard UI A/B Test]((https://github.com/danielagarciagimeno/UI-A-B-Testing-at-Vanguard)
- **Presentation Slides:** [Canva](https://www.canva.com/design/DAGZRhMTMow/3oMVFGT4pyajSYJKEsBG0Q/edit)

---
