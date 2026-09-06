<a href="../README.md">
  <img src="https://img.shields.io/badge/←_Back_to_Main_Portfolio-1F2328?style=for-the-badge&logo=github&logoColor=white" alt="Back to Main Portfolio" />
</a>

# 🐍 Python Data Analytics & Exploratory Data Analysis

---

<a id="bmw-sales-data-eda"></a>
## 🚗 BMW Sales Data Exploratory Data Analysis

<p align="left">
  <a href="https://colab.research.google.com/drive/1OfF5UQLymf75bojdNKr9ZBQgSv0PujlS?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/⚡_Open_in_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Open in Colab" />
  </a>
  <img src="https://img.shields.io/badge/Tools-Python_|_Pandas_|_Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python, Pandas, Seaborn" />
  <img src="https://img.shields.io/badge/Domain-Automotive_Sales-E10600?style=for-the-badge" alt="Automotive Sales" />
</p>

> **Overview:** Evaluated BMW sales data through statistical profiling, time-series line trends, model-level revenue distributions, and correlation heatmaps to surface revenue drivers and linear feature dependencies.

---

### 📝 **Project Details**

* **Title:** BMW Sales Data Exploratory Data Analysis
* **Project Type:** Automotive Retail & Sales Data Science Case Study
* **Tools Used:** Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn
* **Scenario:** Automotive dealerships need clear data on sales movements, vehicle model performance, and pricing variables to optimize inventory allocations.
* **Summary:** Built an EDA pipeline in Google Colab that loads raw BMW dataset records, handles missing entries, generates summary statistics, and visualizes sales trends over time, sales performance across models, and underlying feature correlations.
* **Key Challenges & Solutions:** 
  * *Challenge:* Identifying hidden linear relationships across vehicle specs and pricing while handling irregular transaction dates.
  * *Solution:* Transformed timestamp fields for line plotting, cleaned structural anomalies, and generated a annotated correlation matrix heatmap to evaluate continuous feature relationships.
* **What I Learned:** Time-series line visualizers paired with model-level bar charts reveal seasonal sales spikes faster than simple summary tables, driving smarter inventory planning.
* **Why It Matters:** Helps dealerships focus marketing spend on top-performing car models and adjust pricing based on proven feature correlations.

---

<a id="food-panda-eda"></a>
## 🐼 FoodPanda Food Delivery Operations Analysis

<p align="left">
  <a href="https://colab.research.google.com/drive/1nxPmQH_gcYJ3UpGapr2chTAFOTyun5lO?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/⚡_Open_in_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Open in Colab" />
  </a>
  <img src="https://img.shields.io/badge/Tools-Python_|_Matplotlib_|_Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python, Matplotlib, Seaborn" />
  <img src="https://img.shields.io/badge/Domain-Food_Delivery_&_Logistics-D70F64?style=for-the-badge" alt="Food Delivery & Logistics" />
</p>

> **Overview:** Evaluated order values, delivery times, payment modes, and location distributions for FoodPanda transactions to streamline logistics and pricing strategy.

---

### 📝 **Project Details**

* **Title:** FoodPanda Order & Delivery Operations EDA
* **Project Type:** Operational Logistics Analytics Case Study
* **Tools Used:** Python, Google Colab, Pandas, Seaborn, Matplotlib, NumPy
* **Scenario:** Food delivery platforms must understand how delivery times scale with order size and where regional order values bottleneck fulfillment efficiency.
* **Summary:** Processed delivery datasets by standardizing column names, calculating summary statistics (mean, mode, frequency counts), and plotting distribution histograms, location-based boxplots, payment mode countplots, and scatter plots with fitted regression lines.
* **Key Challenges & Solutions:** 
  * *Challenge:* Spotting geographic order value outliers and confirming whether higher order values directly delay fulfillment time.
  * *Solution:* Combined location-segmented boxplots with an `Order_Value` vs. `Order_Frequency` scatter plot augmented by an automated regression line to evaluate operational trade-offs.
* **What I Learned:** Regression lines fitted over operational scatter plots give instant, visual validation on whether fulfillment times scale with package dimensions or order totals.
* **Why It Matters:** Guides dispatch teams to reallocate delivery fleets toward high-value locations and adjust payment gateway options based on preferred customer checkout habits.

---

<a id="rfm-shopez-analysis"></a>
## 🛍️ ShopEZ Customer Segmentation & RFM Analysis

<p align="left">
  <a href="https://colab.research.google.com/drive/1vC3Macjz01-rd-sn0-U9KOSq80eODVt3?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/⚡_Open_in_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Open in Colab" />
  </a>
  <img src="https://img.shields.io/badge/Tools-Python_|_RFM_Segmentation-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python, RFM Segmentation" />
  <img src="https://img.shields.io/badge/Domain-E--Commerce_Retention-217346?style=for-the-badge" alt="E-Commerce Retention" />
</p>

> **Overview:** Implemented Recency, Frequency, and Monetary (RFM) modeling on ShopEZ retail data to segment buyers, mitigate churn risks, and tailor targeted loyalty campaigns.

---

### 📝 **Project Details**

* **Title:** ShopEZ Customer Lifetime Value & RFM Segmentation
* **Project Type:** Customer Analytics & Retention Strategy Case Study
* **Tools Used:** Python, Google Colab, Pandas, NumPy, Matplotlib (Bar/Pie Charts)
* **Scenario:** ShopEZ needed to identify high-value spenders and at-risk dormant buyers from raw transaction histories to build targeted marketing campaigns.
* **Summary:** Engineered transaction features by creating total purchase columns, computed individual Recency, Frequency, and Monetary metrics, mapped users into behavioral segments, and visualized cohort distributions via pie and bar charts.
* **Key Challenges & Solutions:** 
  * *Challenge:* Translating continuous RFM scores into clear, actionable marketing segments.
  * *Solution:* Built programmatic binning rules in Pandas to categorize shoppers into distinct personas like Loyal Customers, Hibernating, Champions, and Big Spenders.
* **What I Learned:** Hibernating customers can quickly eat into future revenue if ignored; early re-engagement offers yield far higher ROI than cold acquisition.
* **Why It Matters:** Directs marketing spend away from generic blasts by focusing loyalty perks on steady spenders and launching targeted win-back offers to dormant accounts.

---

---

[← Back to Main Portfolio](../README.md)
