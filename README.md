# 🏢 MORSHEDY GROUP Sales & Collection Analytics

## 📌 Project Overview
The real estate company sells units through installment plans. However, the collection data is stored across multiple project worksheets, making it difficult to monitor the overall collection performance. This project builds an end-to-end Power BI solution to centralize, clean, and analyze sales and financial collections.

---

## 🛑 Business Problem
- Data is distributed across 8 project worksheets.
- Installment information is stored in multiple columns and different business states.
- Management needs to identify paid, due, and not-yet-due installments.
- It is difficult to monitor collected and outstanding amounts in one place.
- Management needs visibility into bank exposure and project progress.

---

## 🧹 Data Preparation
The dataset was prepared using:
- Data cleaning
- Handling missing values
- Removing duplicates
- Data type transformation
- Creating calculated columns
- Creating relationships
- Data modeling

---

## 🗄️ Data Model
We create two fact tables because we have two business processes: the unit sold & the installment for the unit sold.

**Schema Components:**
- Fact Sales
- Fact Installments
- Dim Bank
- Dim Customer
- Dim Date
- Dim Project
- Dim Unit

---

## 💡 Key Insights

### Insight 1
**Strong Overall Collection Performance**
- Installment collection gaps reveal critical points where cash flow slows down significantly in later stages.
- Early installments show high commitment rates, while subsequent tiers require proactive follow-up.

### Insight 2
**Outstanding Balance Is Concentrated in Three Projects**
- The total outstanding balance is significant across the portfolio. Three major projects account for the majority of this amount:
  - **Skyline Katamya Compound**
  - **Degla Landmark**
  - **One Kattamea Compound**

### Insight 3
**Later Installments Need Collection Monitoring**
- Collection performance decreases in the later installment stages.
- Outstanding balances in these tiers require targeted recovery strategies before aging further.

---

## 💡 Business Recommendations
Based on the analysis:
1. **Management should maintain** the current collection follow-up process while giving special attention to the remaining large outstanding balances.
2. **Management should give these projects** (Skyline, Degla Landmark, and One Kattamea) closer collection monitoring and review their outstanding installments regularly.
3. **Management should increase follow-up** for later installments before unpaid balances become larger.

---

## 🛠️ Tools & Technologies
- Power BI
- DAX
- Power Query
- Excel

---

## 📂 Repository Structure

```text
Project/
│
├── Dataset/
├── Power BI/
├── Documentation/
└── README.md

___

#👤 Author
Tarek Ahmed
