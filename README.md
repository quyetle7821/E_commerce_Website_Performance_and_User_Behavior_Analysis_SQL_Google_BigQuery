# 📊 What drives purchases & revenue, and where do users drop off in the funnel| eCommerce / Web Analytics | SQL (BigQuery)

_+ Business question : Identify key performance drivers for an eCommerce website and measure the conversation funnel to support marketing & product optimization

_+ Domain : eCommerce / Digital Marketing Analytics (Google Analytics web tracking data)

Author: Lê Trường Quyết<br>
Date : 2025/07/06<br>
Tools Used : SQL (Google BigQuery)<br>

## 📑 Table of Contents 
  1. [📌 Background & Overview](#-background--overview)
  2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)
  3. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

---
## 📌 Background & Overview

### Objective:
### 📖 What is this project about? What Business Question will it solve?
  - This project uses SQL in Google BigQuery to analyze Google Analytics session data from an eCommerce website
  - The goal is to evaluate website performance across traffic, user behavior, and revenue, and to measure the conversion funnel to identify optimization opportunities.

### 👤 Who is this project for?
  - Data Analysts/ BI Analysts
  - E-commerce / Product teams
  - Decision-makers & stakeholders 
  
# Exploring the Dataset
In this project, I write eight queries to explore the dataset and dive deeper into the data to gain insights

## Query 1 : Calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month)
- ### SQL code
  <img width="627" height="187" alt="image" src="https://github.com/user-attachments/assets/84360b54-4966-498a-9cff-30fb0dfb8daa" />
- ### Results
  <img width="909" height="230" alt="image" src="https://github.com/user-attachments/assets/7f8cc994-9ca1-413d-8483-c506f0f924fd" />
  
## Query 2 : Bounce rate per traffic source in July 2017
- ### SQL code
  <img width="725" height="160" alt="image" src="https://github.com/user-attachments/assets/a22b89df-a207-47a1-9891-ae96d959235b" />
- ### Results
  <img width="811" height="565" alt="image" src="https://github.com/user-attachments/assets/23acfc8f-f06e-4db1-acd4-e39a2c9042f1" />
  
## Query 3: Revenue by traffic source by week, by month in June 2017
- ### SQL code
  <img width="720" height="463" alt="image" src="https://github.com/user-attachments/assets/f9998199-1cf7-4beb-bfe8-bdabc38f4a8b" />
- ### Results
  <img width="965" height="629" alt="image" src="https://github.com/user-attachments/assets/e995c9ce-7f8d-4fe1-aeb4-affae68eede7" />

## Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017.
- ### SQL code
  <img width="770" height="595" alt="image" src="https://github.com/user-attachments/assets/77786115-d3b0-4cba-bd8b-45575266b23d" />
- ### Results
  <img width="901" height="197" alt="image" src="https://github.com/user-attachments/assets/ffc11cbb-cb20-402e-8f6a-6a51488fa4ff" />

## Query 05: Average number of transactions per user that made a purchase in July 2017
- ### SQL code
  <img width="889" height="185" alt="image" src="https://github.com/user-attachments/assets/9eae4d38-c668-48fb-ab5f-f12bb0c63ffa" />
- ### Results
  <img width="918" height="173" alt="image" src="https://github.com/user-attachments/assets/ef1c28b0-d399-4df5-8030-6473f550ebb1" />

## Query 06: Average amount of money spent per session. Only include purchaser data in July 2017
- ### SQL code
  <img width="946" height="190" alt="image" src="https://github.com/user-attachments/assets/597317cc-5994-4af2-93a5-4767e06aa482" />
- ### Results
  <img width="920" height="180" alt="image" src="https://github.com/user-attachments/assets/f680981a-6774-4335-9504-d1239782d12a" />

## Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.
- ### SQL code
  <img width="721" height="464" alt="image" src="https://github.com/user-attachments/assets/c62d521f-388a-48d8-b9ba-0a6075a5f995" />
- ### Results
  <img width="906" height="471" alt="image" src="https://github.com/user-attachments/assets/ad410763-4dde-41d0-a014-017becf8254c" />

## Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017. For example, 100% product view then 40% add_to_cart and 10% purchase.
- ### SQL code
  <img width="1329" height="405" alt="image" src="https://github.com/user-attachments/assets/407fd495-a1d7-44ca-a16f-7664d8517b50" />
- ### Results
  <img width="1107" height="238" alt="image" src="https://github.com/user-attachments/assets/e2f8ad2d-624b-4ae8-8ce0-f6de62042d44" />













  
