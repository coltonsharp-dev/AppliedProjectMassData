# AppliedProjectMassData
Automated data-driven teacher dashboard for American Leadership Academy – Fall 2025. Built with Google Sheets, CodePen, and CSV-based analytics to visualize student performance trends, RAISE values, and weekly growth metrics across CTE, AP Pre-Calculus, AP Calculus, and Intro to Computer Science classes.


# ALA Teacher Dashboard – Fall 2025

This repository contains the working files, CSV data, and scripts behind **Mr. Sharp’s All-in-One Teacher Dashboard** used at **American Leadership Academy – Vistancia (Peoria, AZ)**.  
The project connects **Google Sheets**, **CodePen**, and **GitHub raw CSV hosting** to produce a live, visual classroom analytics system.

## 🔍 Overview
The dashboard visualizes real and simulated student data for Weeks 1–11 (pre–Fall Break) across four core high-school courses:
- Period 3: **CTE – App Design**
- Period 4: **AP Pre-Calculus**
- Period 5: **AP Calculus AB**
- Period 7: **Intro to Computer Science**

Each dataset tracks:
- Assessment scores and proficiency levels  
- Behavior, engagement, and attendance  
- AI feedback scores and teacher reflections  
- RAISE values (Respect, Accountability, Integrity, Service, Excellence)  
- Rolling averages and performance ratios  

## ⚙️ Data Generation
The `ALA_MasterData_Fall2025` CSVs are generated from a **Google Sheets automation engine** that applies random ± variance formulas to simulate week-to-week growth.  
Each new week’s dataset shows a **positive trend in student performance** across all key metrics for administrative review and longitudinal analysis.

## 🧠 Tech Stack
- **Google Sheets** – dynamic data engine + automation formulas  
- **CodePen.io** – live dashboard front-end (HTML/CSS/JS)  
- **GitHub** – static data hosting for CSV & JSON  
- **Chart.js / D3.js (optional)** – visualization library integration

## 📊 Features
- Interactive visualizations of student progress
- Week-to-week data trend analysis  
- Class-level and student-level filtering  
- Honors and intervention tracking  
- Ready-to-import CSV/JSON datasets

## 🧩 File Structure
ALA_MasterData_Fall2025/
│
├── Week_09.csv
├── Week_10.csv
├── Week_11.csv
├── ALA_MasterData_Fall2025.json
└── README.md


## 🔒 Note on Data
All student names are **pseudonymized for confidentiality**.  
Simulated records are used to demonstrate visual, instructional, and analytic features of the dashboard.

---

**Maintained by:**  
👨‍🏫 *Colton H. Sharp*  
American Leadership Academy – Vistancia  
Fall 2025 | Teacher Dashboard Research Project  
