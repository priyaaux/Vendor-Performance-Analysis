📊 Vendor Performance Analysis Dashboard..!!

📌 Project Overview
	-This project focuses on analyzing vendor performance using key supply chain metrics such as on-time delivery, defect rate, compliance, lead time,       	 & cost savings.  
	-The goal is to identify **top-performing vendors**, **risk vendors**, and **improvement opportunities** through an interactive Power BI dashboard.

🛠️ Tools & Technologies
	- Python(Pandas, NumPy, matplotlib, seaborn)
	- Jupyter Notebook
	- Power BI
	- DAX (Data Analysis Expressions)
	- Microsoft Excel / CSV
	- GitHub


📂 Data Source
- Dataset sourced from **Kaggle**
- Raw vendor transaction-level data containing:
  - Supplier information
  - Order dates & delivery status
  - Quantity & pricing
  - Defect and compliance indicators


 🔄 Project Workflow

	1️⃣ Data Collection
	- Downloaded raw vendor dataset from Kaggle.

	2️⃣ Data Cleaning & Transformation (Python)
	- Performed in **Jupyter Notebook**
	- Tasks included:
  		- Handling missing values
  		- Date formatting
  		- Feature engineering (On-Time Flag, Lead Time)
  		- Aggregation at vendor level
	- Output:
 			- clean_vendor_data.csv
  			- vendor_summary.csv

	3️⃣ Data Loading (Power BI)
	- Clean CSV files loaded into Power BI
	- Data model created with proper relationships

 		4️⃣ DAX Calculations
	Key measures created using DAX:
	- Vendor Score
	- Vendor Rank
	- Average On-Time Delivery %
	- Average Defect Rate
	- Compliance Rate
	- Cost Saving %

	5️⃣ Dashboard Design
	Designed an **interactive and visually appealing dashboard** with:
	- KPI cards
	- Ranking tables
	- Bar, line, scatter, donut, gauge, and treemap visuals
	- Slicers for vendor filtering


	📈 Dashboard Pages

	 🔹 Page 1: Vendor Performance Overview
	- Top Ranked Vendor
	- Average On-Time Delivery %
	- Average Defect Rate
	- Compliance KPI
	- Vendor ranking table
	- Monthly On-Time Delivery trend
	- Vendor score comparison

	 🔹 Page 2: Detailed Analysis by Supplier & Category
	- Item category-wise quantity analysis
	- Supplier vs item category comparison
	- Quantity distribution by vendor rank
	- Defect rate vs On-Time performance
	- Monthly Lead Time trend


 🧠 Key Insights

- Identified top-performing vendors based on composite score
- Highlighted vendors with high defect rates and low compliance
- Analyzed category-wise contribution to total quantity
- Detected seasonal trends in delivery performance and lead time



 📷 Dashboard Preview

 Page 1 – Overview
![Dashboard Page 1](dashboards/Dashboard Page1.png)

 Page 2 – Detailed Analysis
![Dashboard Page 2](dashboards/Dashboard Page2.png)


 📌 Conclusion

This project demonstrates an **end-to-end data analytics workflow**, combining Python for data preprocessing and Power BI for business intelligence and storytelling.  
It showcases practical skills in **data cleaning, DAX modeling, and dashboard design**.

📬 Contact & LinkedIn

Feel free to connect if you'd like help with dashboards, data analysis, or Power BI projects.

🔗 **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/priya-more-61a967259/)
Also, you can check the **full dashboard video** I uploaded on my LinkedIn account.

🚀 Author

**Priya More**  
Aspiring Data Analyst | Power BI | Python | SQL  

📬 Feel free to connect or provide feedback!
