# Flipkart Customer Support EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Flipkart's Customer Support dataset to uncover insights about operational efficiency and customer satisfaction (CSAT). The analysis focuses on understanding patterns in issue resolution, agent performance, support channels, and product categories, with the goal of improving customer experience and optimizing support operations.

**Dataset:** `Customer_support_data.csv`  
**Columns include:**
- Unique id, channel_name, category, Sub-category, Customer Remarks, Order_id, order_date_time  
- Issue_reported_at, issue_responded, Survey_response_Date, Customer_City  
- Product_category, Item_price, connected_handling_time, Agent_name  
- Supervisor, Manager, Tenure Bucket, Agent Shift, CSAT Score

---

## 🎯 Problem Statement
Flipkart aims to enhance customer satisfaction by identifying factors that affect support quality, including agent performance, response time, handling time, and channel effectiveness. The dataset provides insights to improve operations and deliver a better customer experience.

---

## 🎯 Business Objective
- Improve **customer satisfaction (CSAT)** across all support channels.  
- Reduce **connected handling time** and **issue response delays**.  
- Optimize **agent allocation and shift management**.  
- Identify **product categories and channels** requiring focused attention.  
- Provide **actionable recommendations** to improve operational efficiency.

---

## 🛠 Libraries Used
- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`  
- Data Visualization: Scatter plots, bar charts, boxplots, pie charts, heatmaps, pair plots

---

## 🔍 Key Analysis & Visualizations
1. **CSAT Score vs Connected Handling Time** – Understanding impact of resolution speed on satisfaction  
2. **CSAT Score vs Issue Response Time** – Evaluating timeliness of support  
3. **Average CSAT by Product Category** – Identifying product areas needing improvement  
4. **CSAT by Agent Tenure Bucket** – Effect of agent experience on satisfaction  
5. **CSAT by Agent Shift and Tenure** – Combined impact of shift timing and agent experience  
6. **Distribution of Issues by Support Channel** – Proportion of tickets across channels  
7. **Correlation Heatmap** – Relationships between numeric variables (handling time, response time, item price, CSAT)  
8. **Pair Plot** – Visual overview of relationships and distributions of numeric variables

---

## 📈 Key Insights
- **Efficiency matters:** Longer handling times and delayed responses negatively impact CSAT.  
- **Experience matters:** Higher-tenure agents maintain higher CSAT scores.  
- **Shift and workload management:** Certain shifts with low-tenure agents have lower CSAT.  
- **Category-specific trends:** High-value product categories require more attention to improve satisfaction.  
- **Channel management:** Chat is the most used channel and needs adequate staffing.

---

## 💡 Business Recommendations
1. Optimize handling and response times through **training, automation, and process improvements**.  
2. Allocate **experienced agents to high-complexity cases** and mentor low-tenure agents.  
3. Monitor **high-demand support channels** and ensure proper staffing.  
4. Focus on **product categories with lower CSAT** for process improvements.  
5. Regularly track KPIs such as **CSAT, handling time, and issue response time** to proactively address issues.

---

## ✅ Conclusion
The EDA confirms that **customer satisfaction is strongly influenced by agent efficiency, experience, and response speed**. By leveraging these insights, Flipkart can optimize support operations, improve resource allocation, and ultimately enhance customer experience and loyalty.

---

## 📂 Dataset
The dataset used in this project can be found as:  
`Customer_support_data.csv`  
