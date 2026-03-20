# 📊 Customer Segment Profiles

## 📌 Overview

This document presents the customer segments identified using clustering techniques (K-Means and Hierarchical Clustering). Each segment represents a distinct group of customers with similar behavioral and financial characteristics.

These segments are used to:

* Understand customer behavior
* Build segment-specific prediction models
* Design targeted business strategies

---

## 🧠 Segmentation Methodology

* **Primary Algorithm:** K-Means Clustering
* **Number of Segments:** 3
* **Features Used:**

  * Tenure
  * MonthlyCharges
  * TotalCharges
  * Contract
  * PaymentMethod
  * PaperlessBilling
  * SeniorCitizen

---

## 👥 Segment 1: Premium Spenders

### 📌 Key Characteristics

* High monthly charges
* High total spending
* Longer tenure (loyal customers)
* Mostly long-term contracts (annual plans)
* Lower churn rate

### 📊 Behavioral Insights

* These customers generate **high revenue**
* Strong brand loyalty
* Less price-sensitive

### ⚠️ Risk Level

🟢 Low churn risk

### 🎯 Business Strategy

* Offer loyalty programs and premium benefits
* Provide VIP customer support
* Early access to new services

---

## 👥 Segment 2: Budget Conscious Customers

### 📌 Key Characteristics

* Low monthly charges
* Low total spending
* Shorter tenure
* Mostly month-to-month contracts
* Higher churn rate

### 📊 Behavioral Insights

* Highly price-sensitive
* Likely to switch for better deals
* Low engagement with premium features

### ⚠️ Risk Level

🔴 High churn risk

### 🎯 Business Strategy

* Provide discounts and bundled offers
* Introduce affordable long-term plans
* Offer incentives for contract upgrades

---

## 👥 Segment 3: Young / Moderate Users

### 📌 Key Characteristics

* Moderate monthly charges
* Medium tenure
* High adoption of paperless billing
* Digital payment methods
* Balanced spending pattern

### 📊 Behavioral Insights

* Tech-savvy and convenience-driven
* Moderate loyalty
* Influenced by service experience

### ⚠️ Risk Level

🟡 Medium churn risk

### 🎯 Business Strategy

* Improve mobile and digital experience
* Personalized recommendations
* Flexible subscription plans

---

## 📈 Segment Distribution (Example)

| Segment | Avg Tenure             | Avg Monthly Charges | Avg Total Charges | Churn Rate |
| ------- | ---------------------- | ------------------- | ----------------- | ---------- |
| 0       | *40.700565*            | *117.920904*        | *3762.627119*     | *0.067797* |
| 1       | *33.222222*            | *85.650000	*        | *4591.727778*     | *0.111111* |
| 2       | *35.538462*            | *143.559441*        | *4380.734266*     | *0.146853* |

---

## 📊 Key Insights Summary

* Premium customers contribute the **highest revenue but lowest churn**
* Budget customers have the **highest churn risk**
* Moderate users represent the **largest segment with growth potential**

---

## 🚀 Business Impact

By leveraging these segments, businesses can:

* Increase retention through targeted strategies
* Optimize marketing campaigns
* Improve customer lifetime value (CLV)
* Reduce churn using segment-specific interventions

---

## 🏁 Conclusion

Customer segmentation enables a deeper understanding of diverse customer groups, allowing for **data-driven decision-making** and **personalized business strategies**. This approach enhances both customer satisfaction and business profitability.



