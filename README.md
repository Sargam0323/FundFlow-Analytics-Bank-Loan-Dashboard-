# FundFlow-Analytics-Bank-Loan-Dashboard-
FundFlow Analytics is a professional and interactive Power BI dashboard designed to uncover actionable insights from loan data. It enables stakeholders to track loan application patterns, assess borrower profiles, evaluate risk, and visualize the overall financial health of loan portfolios.

# 🎯 Project Objective
To build an intuitive and insightful dashboard that:
- Visualizes loan application trends and outcomes
- Tracks key metrics like funded amounts, interest rates, and approval ratios
- Identifies borrower patterns based on state, purpose, employment length, and more
- Assists financial analysts in making data-driven lending decisions

# 📊 Key Features
- ✅ Clean, modern layout with customized theme
- ✅ KPI cards for fast summary of loan performance
- ✅ Donut, bar, and line charts for interactive storytelling
- ✅ Map visuals for geo-based analysis
- ✅ Filterable tables for detailed record exploration
- ✅ User-friendly slicers for dynamic segmentation

# 📁 Dashboard Sections
# 📌 Summary Page
- Key performance metrics: Applications, Funded Amount, Amount Received, Avg. Interest Rate, DTI
- Good vs Bad loan segmentation
- Loan purpose breakdown
- Loan performance by grade
# 📌 Overview Page
- Monthly trend of amount received
- Loan distribution by employee length, term,home ownership
- Purpose-wise funded amount              - - Geo map showing state-wise loan activity
# 📌 Details Page
- Full loan record table
- Filters: State, Grade, Purpose, Loan Status
- Fields: ID, Funded Amount, Int Rate, DTI, Installments, etc.
# 🧠 Key Insights
- Majority of loans are issued for debt consolidation and credit card repayment.
- Loans with longer employment tenure often have higher approval and funding.
- Over 85% of loans in the dataset are categorized as "Good".
- Interest rates vary significantly based on loan grades and terms.
# ⚙️ Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions) for measures
- Power Query Editor for data transformation
- Data visualization best practices
# 🧮 DAX Measures Used
- Total Applications = COUNT('LoanData'[id])
- Total Funded = SUM('LoanData'[Funded Amount])
- Avg Int Rate = AVERAGE('LoanData'[Int Rate])
- Good Loan %, Bad Loan % using CALCULATE + DIVIDE
- Custom ratios like Avg DTI, Loan Performance %
# 📂 Dataset Information
The dataset includes:
- Loan ID, Term, Purpose, Grade/Sub-grade
Funded Amount, Amount Received, Interest Rate
- Employment Length, Home Ownership, Address State
- Loan Status (Fully Paid, Charged Off, etc.)
- Debt-to-Income Ratio (DTI)
> 📌 Note: Dataset used for learning and portfolio demonstration purposes only
# 🚀 How to Use
- Open FundFlow_Analytics_Dashboard.pbix in Power BI Desktop
- Use slicers on the left to filter by state, grade, purpose, and status
- Navigate through the 3 report pages: Summary, Overview, and Details
- Hover over charts for tooltips and deeper insights
