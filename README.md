<p align="center">
  <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="200" alt="Skills Network Logo">
  </a>
</p>

# Exploring and Pre-processing a Dataset using Pandas 🐼

> **Estimated Time:** 30 minutes  
> **Author:** [Alex Aklson](https://www.linkedin.com/in/aklson/)  
> **Contributors:** [Jay Rajasekharan](https://www.linkedin.com/in/jayrajasekharan), [Ehsan M. Kermani](https://www.linkedin.com/in/ehsanmkermani), [Slobodan Markovic](https://www.linkedin.com/in/slobodan-markovic), [Weiqing Wang](https://www.linkedin.com/in/weiqing-wang-641640133/), [Dr. Pooja](https://www.linkedin.com/in/p-b28802262/)

---

## 🎯 Objectives

After completing this lab, you will be able to:

- Explore datasets using **Pandas**
- Pre-process data for visualization
- Perform filtering, sorting, and indexing operations
- Apply basic and intermediate Pandas techniques for data wrangling

---

## 📘 Introduction

This project serves as a refresher on the **Pandas** library.  
You’ll learn how to explore and clean data effectively before visualization.  
The dataset used focuses on **immigration to Canada from 1980 to 2013** — sourced from the [United Nations](https://www.un.org/development/desa/pd/data/international-migration-flows).

If you wish to learn more about data cleaning and transformation using Pandas, check out other IBM Skills Network courses.

---

## 🧾 Table of Contents

1. [Exploring Datasets with Pandas](#exploring-datasets-with-pandas)  
2. [Dataset: Immigration to Canada (1980–2013)](#dataset)  
3. [Pandas Basics](#pandas-basics)  
4. [Indexing and Selection](#indexing-and-selection)  
5. [Filtering Data](#filtering-data)  
6. [Sorting Values](#sorting-values)

---

## 🗂️ Dataset

**Source:** [International Migration Flows - The 2015 Revision (UN DESA)](https://www.un.org/development/desa/pd/data/international-migration-flows)

This dataset contains annual immigration data to and from selected countries.  
For this lab, we focus on **Canadian immigration data (1980–2013)**.

📥 Download the dataset:  
[Canada.xlsx](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Canada.xlsx)

---

## ⚙️ Requirements

Install dependencies before running the notebook:

```bash
pip install pandas numpy openpyxl==3.0.9
