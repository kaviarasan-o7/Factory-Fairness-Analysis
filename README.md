# Fairness Analysis Dashboard

This repository contains a data visualization project built in Tableau to analyze and report on the fairness of job roles across multiple factory locations.

---

## 🚀 Project Overview

The goal of this project is to provide a clear, at-a-glance view of potential inequality or discrimination within an organization's job structure. By assigning an "Equality Class" to each job role at different sites, this dashboard helps HR and leadership teams identify systemic issues and areas that require further investigation. The visualization is designed to be simple, impactful, and easy to interpret.

---

## ✨ Key Features & Implementation

* **Data Source:** The visualization is based on a structured dataset containing factory locations, job roles, and a pre-determined equality classification.
* **Visualization Tool:** The dashboard was designed and built entirely in **Tableau**.
* **Core Visualization:** A central table that uses conditional color formatting to highlight the status of each role, based on the following legend:
    * 🟦 **Fair:** Indicates no significant issues were found.
    * 🟧 **Highly Discriminative:** Indicates a high probability of discriminatory practices.
    * 🟥 **Unfair:** Indicates evidence of unfairness in the role's structure or compensation.

---

## 📊 Key Insights & Observations

The dashboard immediately reveals several critical patterns:

* **Senior-Level Concerns:** Top-level management roles such as 'C-Level', 'VP', and 'Director' are flagged as **Highly Discriminative** specifically at the Daikibo Meiyo and Seiko factories.
* **Systemic Operational Issues:** The 'Operational Support' role is consistently marked as **Unfair** or **Highly Discriminative** across multiple locations, suggesting a widespread issue with this particular job function.
* **Positive Engineering Trend:** Most technical roles, including 'Engineer', 'Jr. Engineer', and 'Sr. Engineer', are classified as **Fair** across all factories, indicating healthier practices in this department.

---

## 📂 Repository Contents

* `/Sheet 1.png`: A static screenshot of the final Tableau dashboard for quick previewing.
* `Equality Table_Edited.xlsx.twbx`: The complete Tableau Packaged Workbook. This file can be opened with Tableau Desktop or the free Tableau Reader for interactive viewing.

---

## ☁️ About This Project

As this project was built in Tableau, it cannot be "run" like a piece of code. This repository serves as a portfolio piece to document the project and showcase skills in data visualization, data interpretation, and dashboard creation.
