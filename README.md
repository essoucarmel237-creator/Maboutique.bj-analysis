# Maboutique.bj Platform Analysis 📊

An exploratory data audit and strategic presentation analyzing **maboutique.bj** (an e-commerce platform) to uncover operational anomalies, evaluate store activation bottlenecks, and measure the impact of app activation on customer engagement.

---

##  Project Overview
The goal of this project was to analyze the activation status of stores on the maboutique.bj platform to understand why only a small fraction of stores maintain active applications, uncover operational discrepancies within the activation process, and provide data-driven recommendations to leadership.

---

##  Key Findings & Insights

* **Low Initial Activation Rate:** Out of 103 total stores on the platform, only **8.24%** (8 stores) had genuinely active application.
* **Data Hygiene & Test Stores:** The audit uncovered **18 test stores** (lacking both professional profile logos and products, yet mistakenly flagged as active) which were filtered out, leaving a clean analysis pool of 85 stores.
* **Activation Process Errors:** **15 stores** with fewer than the mandatory 10 products were incorrectly activated by the operations team.
* Ultimately, only **7 stores** fully met all strict platform prerequisites.
* **Impact on Customer Traffic:** Analyzing the fully compliant stores revealed a strong positive correlation with user engagement:
  * Out of **7** properly activated stores, **6** received app downloads (~85.71%).
  * Of those downloaded apps, **5** generated active users (~83.33%).

---

##  Strategic Recommendations

1. **Re-engage Inactive Stores:** Target the 78 unactivated stores (91.76% of the total base) and guide them to complete their product catalogs (minimum 10 products) and profile setups.
2. **Improve Internal Quality Control:** Address oversight by the activation team to prevent premature store approvals (such as the 15 stores with insufficient products).

---

## 🛠️ Methodology & Tools
* **Data Audit & Hygiene:** Filtering testing artifacts, cross-checking prerequisite rules (catalog size $\ge$ 10 products + professional logo), and calculating conversion percentages.
* **Presentation Design:** Structured and designed a professional slide deck to present insights and recommendations to stakeholders.

---

## 📂 Repository Structure
```text
├── presentation/         # Maboutique.bj Presentation.pdf (Full slide deck)
└── README.md             # Project documentation & summary
