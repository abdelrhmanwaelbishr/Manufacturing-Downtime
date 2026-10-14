# 🏭 Manufacturing Downtime Analysis
**Data Analytics · Production Efficiency · Downtime Reduction**  
*Graduation Project — Digital Egypt Pioneers Initiative (DEPI)*

---

## 📌 1. Project Overview & Description
Manufacturing downtime can reduce production efficiency, delay operations, and affect the effective use of manufacturing resources. 

This project analyzes factory production and downtime data—including production batches, product reference information, operator details, and recorded downtime factors—to understand the root causes of lost production time, compare performance across products and operators, and help management make data-driven decisions to improve operational efficiency.

---

## 🎯 2. Project Objectives
1. **Analyze Recorded Downtime:** Identify the main factors contributing most to total downtime and occurrences.
2. **Measure Production Performance:** Evaluate total and average batch duration alongside downtime indicators.
3. **Compare Products & Operators:** Benchmark production duration and downtime across different products, sizes, flavors, and operators.
4. **Identify Patterns & Trends:** Track daily production and downtime trends and compare actual batch times against minimum reference times.
5. **Ensure Data Quality:** Perform systematic inspection, cleaning, and validation of duplicates, missing values, and reference keys.
6. **Build Interactive Dashboards:** Develop a multi-page Power BI solution with meaningful KPIs, slicers, and actionable recommendations.

---

## 🗓️ 3. Project Roadmap & Deadlines

| Phase | Deadline | Key Deliverables | Status |
| :--- | :--- | :--- | :--- |
| **Phase 1: Planning & Requirements** | **Oct 16** | • Project description & objectives<br>• Project phases & task breakdown<br>• Team roles & tools used<br>• 40 Business Requirements defined | ✅ Completed |
| **Phase 2: Data Design & Analysis** | **Nov 06** | • Dataset understanding & Data Dictionary<br>• Data quality inspection & issues log<br>• Data cleaning plan<br>• Data Model / Star Schema design (ERD) | ⏳ Upcoming |
| **Phase 3: Implementation** | **Nov 30** | • Data cleaning & Power Query transformations (Unpivot)<br>• DAX calculated columns & measures<br>• 4 Interactive Power BI Dashboards + Home Page<br>• Output validation & testing | ⏳ Upcoming |
| **Phase 4: Final Delivery** | **Dec 04** | • Final Analytical Report<br>• Final Presentation<br>• 1–2 Minute Project Demo Video | ⏳ Upcoming |

---

## 👥 4. Team Members & Responsibilities

| # | Team Member | Role | Assigned Dashboard | Key Responsibilities |
| :-: | :--- | :--- | :--- | :--- |
| 1 | **Mohammed Abd Ellatif Mohammed Emish** | Team Leader & Data Analyst | **Home Page** & **Dashboard 1:** Production Overview | Coordinate tasks & monitor deadlines; participate in Excel data cleaning; analyze overall production KPIs; design Home Page navigation & Production Overview dashboard. |
| 2 | **Abdelrhman Wael Bishr Mokhtar** | Data Analyst & Dashboard Developer | **Dashboard 2:** Downtime Analysis | Inspect, clean, and validate data using Excel/Power Query; analyze downtime factors, durations, occurrences, and daily trends; develop Downtime Analysis dashboard. |
| 3 | **Mohamed Ali Fawzy Ali** | Data Analyst & Dashboard Developer | **Dashboard 3:** Production Time Analysis | Prepare data & perform EDA; analyze batch durations, daily patterns, and compare actual duration with minimum product batch time; develop Production Time Analysis dashboard. |
| 4 | **Ahmed Hussien Hassan Galala** | Data Analyst & Dashboard Developer | **Dashboard 4:** Product & Operator Analysis | Perform data quality checks & preparation; compare batch counts, duration, and downtime across products, flavors, sizes, and operators; develop Product & Operator dashboard. |

---

## 🛠️ 5. Tools Used
* **Microsoft Excel:** Initial data inspection, cleaning, validation, handling missing/duplicate records, and exploratory data analysis (EDA).
* **Microsoft Power Query:** Data transformation, reshaping (Unpivoting `Line downtime` table), and data quality checks (Merge/Anti-join checks).
* **Microsoft Power BI Desktop & DAX:** Star Schema data modeling, calculated columns, DAX measures, KPIs, and interactive dashboard development.

---

## 📋 6. The 40 Business Requirements

<details>
<summary><b>🔹 Category 1: Downtime Analysis (REQ-01 to REQ-10) — <i>Click to expand</i></b></summary>

| ID | Requirement |
| :--- | :--- |
| **REQ-01** | Calculate the total recorded downtime. |
| **REQ-02** | Calculate the average downtime per batch. |
| **REQ-03** | Identify the downtime factor with the highest total downtime. |
| **REQ-04** | Identify the most frequently recorded downtime factor. |
| **REQ-05** | Calculate the total downtime for each factor. |
| **REQ-06** | Calculate the percentage of total downtime contributed by each factor. |
| **REQ-07** | Count the batches with recorded downtime. |
| **REQ-08** | Identify the batches with the highest downtime. |
| **REQ-09** | Analyze daily downtime trends. |
| **REQ-10** | Count the recorded downtime occurrences for each factor. |
</details>

<details>
<summary><b>🔹 Category 2: Production Time Analysis (REQ-11 to REQ-20) — <i>Click to expand</i></b></summary>

| ID | Requirement |
| :--- | :--- |
| **REQ-11** | Calculate the total recorded production duration. |
| **REQ-12** | Calculate the average production duration per batch. |
| **REQ-13** | Identify the batch with the longest production duration. |
| **REQ-14** | Identify the batch with the shortest production duration. |
| **REQ-15** | Count the batches that exceeded their product's minimum batch time. |
| **REQ-16** | Calculate the average production duration for each product. |
| **REQ-17** | Compare recorded batch duration with the product's minimum batch time. |
| **REQ-18** | Calculate the average batch duration for each day. |
| **REQ-19** | Count the recorded batches for each day. |
| **REQ-20** | Identify batches that took longer than other batches of the same product. |
</details>

<details>
<summary><b>🔹 Category 3: Product and Operator Analysis (REQ-21 to REQ-30) — <i>Click to expand</i></b></summary>

| ID | Requirement |
| :--- | :--- |
| **REQ-21** | Count the recorded batches for each product. |
| **REQ-22** | Identify the product with the highest number of batches. |
| **REQ-23** | Identify the product with the lowest number of batches. |
| **REQ-24** | Calculate the total downtime for each product. |
| **REQ-25** | Calculate the average downtime per batch for each product. |
| **REQ-26** | Compare production duration across products. |
| **REQ-27** | Count the batches handled by each operator. |
| **REQ-28** | Calculate the average batch duration for each operator. |
| **REQ-29** | Calculate the total recorded downtime associated with batches handled by each operator. |
| **REQ-30** | Count the batches with recorded downtime for each operator. |
</details>

<details>
<summary><b>🔹 Category 4: Trends, Data Quality, and Dashboard (REQ-31 to REQ-40) — <i>Click to expand</i></b></summary>

| ID | Requirement |
| :--- | :--- |
| **REQ-31** | Analyze the distribution of batches across the available dates. |
| **REQ-32** | Identify the dates with the highest recorded downtime. |
| **REQ-33** | Analyze the distribution of batches by product size. |
| **REQ-34** | Analyze the distribution of products by flavor. |
| **REQ-35** | Identify duplicate batch IDs in the production data. |
| **REQ-36** | Identify missing values in important data columns. |
| **REQ-37** | Validate start and end times for production duration calculations. |
| **REQ-38** | Validate downtime factor IDs against the downtime factor reference table. |
| **REQ-39** | Enable dashboard filtering by date, product, operator, and downtime factor where applicable. |
| **REQ-40** | Display the main production and downtime KPIs and charts in an interactive dashboard. |
</details>

---

## 📂 7. Repository Structure
* `Phase_1_Planning_&_Requirements/`: Project proposal, team roles, 40 business requirements, and DAX implementation guide.
* `Phase_2_Data_Understanding_&_Design/`: Data dictionary, data quality assessment, cleaning plan, and Star Schema diagram *(Due Nov 6)*.
* `Phase_3_Implementation_&_Dashboard/`: Cleaned dataset, DAX scripts, and Power BI `.pbix` dashboards *(Due Nov 30)*.
* `Phase_4_Final_Delivery/`: Final report, presentation slides, and project demo video *(Due Dec 4)*.
