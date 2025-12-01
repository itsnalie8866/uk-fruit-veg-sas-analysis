# **UK Fruit & Vegetable Consumption Analysis (1975–2015)**

**Tools:** SAS (DATA Step, PROC SORT, PROC PRINT, PROC TABULATE)
**Dataset:** UK Government Family Food Dataset
**Grade:** 90/100

This repository contains the full SAS coursework submission for **MANG1041 – Business Analytics Programming I**.
It includes the SAS program, coursework brief, dataset, and the submitted Word/PDF files with detailed comments and outputs.

---

## 📁 **Contents**

* **Coursework_Ans_SAS1.docx / .pdf** – full SAS solution with comments and explanations  
* **Coursework_Ques_SAS1.pdf** – full assessment brief and task descriptions (Tasks 1–8) 
* **food.xlsx** – dataset used for all SAS tasks

---

## 📌 **Overview**

This project explores **UK household fruit and vegetable consumption** over a 40-year period (1975–2015).
The goal was to uncover long-term dietary trends, highlight the most purchased fruits and vegetables, and analyse changes across major food categories.

The work involved importing, cleaning, transforming, ranking, and summarising the dataset using SAS Base, including a multi-dimensional summary table created with **PROC TABULATE**.

---

## 🎯 **Objectives**

* Identify the **most purchased fresh fruits** in 2015
* Analyse **long-term (40-year) trends** in vegetable consumption
* Compare **category-level consumption** in 2015
* Practise core SAS programming:
  data steps, sorting, filtering, variable derivation, and tabulation

---

## 🛠️ **Methodology**

### **1. Importing & Preparing the Dataset**

* Imported *food.xlsx* using `proc import`
* Verified variable types and labels before processing

### **2. Identifying Top Fresh Fruits (2015)**

* Sorted the dataset by `quantity2015`
* Filtered items labelled **Fresh fruit**
* Output highlighted the UK's most consumed fruits

### **3. Analysing 40-Year Vegetable Growth**

* Created a vegetable-only dataset (excluding potatoes)
* Kept: `food`, `quantity1975`, `quantity2015`
* Added a new variable: **change40 = quantity2015 / quantity1975**
* Ranked vegetables by growth and displayed the top five

### **4. Category-Level Summary Using TABULATE**

* Learnt and applied `proc tabulate`
* Produced a summary table of **2015 consumption by category1 within category2**, matching the brief requirements on page 2

---

## 📊 **Key Insights**

### ⭐ **Most Popular Fresh Fruits in 2015**

* Bananas were the most purchased fruit
* Apples remained a consistent long-term staple
* Soft fruits and stone fruits have grown steadily in popularity

### ⭐ **Vegetables with Highest Growth (1975 → 2015)**

Examples from the ranked output:

* Courgettes and stem vegetables → strong increase
* Fresh root vegetables → rising popularity
* Prepared vegetable products → significant growth
* Traditional greens (e.g., cabbage) showed decline in line with modern preferences

### ⭐ **Category-Level Trends (2015)**

* Fresh & processed vegetables form the largest category
* Potato consumption has declined steadily across the four decades

---

## 💡 **Technical Skills Demonstrated**

* SAS DATA Step programming
* Sorting, filtering, and dataset restructuring
* Creating derived variables
* Using `PROC PRINT`, `PROC SORT`, and `PROC TABULATE`
* Commenting code clearly and logically
* Analytical interpretation of long-term trends

---

## 🏁 **Outcome**

This project strengthened my SAS programming skills and improved my ability to analyse government datasets, interpret long-term consumption patterns, and communicate insights concisely.
The coursework achieved a **90/100** grade, with positive feedback on correctness and structure.
