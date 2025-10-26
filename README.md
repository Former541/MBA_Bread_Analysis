# MBA_Bread_Analysis
📋 Assignment Rubric Compliance
Course: Data Mining
Assignment: Market Basket Analysis with Apriori (10 Points)
Student Submission

✅ Part 1: Transactional Dataset

Real-world bakery transaction data from The Bread Basket (Edinburgh)
9,684 unique transactions, 20,507 item entries
Period: October 30, 2016 - December 3, 2016
Format suitable for Market Basket Analysis (multiple items per transaction)

✅ Part 2: Data Preprocessing
Loaded with pandas (Section 2)
Comprehensive 5-step cleaning process (Section 4)
One-hot encoding using TransactionEncoder (Section 6)
Data quality assessment documented (Section 3)

✅ Part 3: Apriori Algorithm Implementation
Uses mlxtend library as specified in rubric
Threshold testing performed (Section 7)
Apriori algorithm applied with 3% minimum support
Frequent itemsets generated and analyzed
Follows methodology from reference article

✅ Part 4: Interpretation and Analysis
All 5 key metrics calculated: Support, Confidence, Lift, Leverage, Conviction
Actionable business insights throughout (Sections 8-11)
Business priority classification (HIGH/MEDIUM/LOW)
Strategic recommendations from immediate to long-term (Section 12)
Negative association analysis included (Section 11)
Goes beyond listing rules - provides detailed business implications

✅ Part 5: Summary and Deliverables
Written methodology summary (Sections 1-12, Appendix)
Top association rules displayed in tables (Section 8)
Thoughtful analysis with actionable strategies (Sections 10, 12)
Multiple visualizations:
Top items bar charts
Transaction size distributions
KPI scatter plots and histograms
Item pair visualizations
Executive summary with ROI projections (Section 12)
📝 Note on Part 6 (Interactive Application):

✅Part 6 requires building an interactive web application with Cursor/Windsurf
This notebook provides the complete analytical foundation (Parts 1-5)
The interactive application component would be developed separately
All data, rules, and metrics are ready for integration into an app
Business Context:
Company: The Bread Basket - A bakery located in Edinburgh, Scotland

Business Challenge:

Optimize product placement in-store
Identify cross-selling opportunities
Create effective product bundles
Increase average transaction value
Improve customer satisfaction through better recommendations
Dataset:

Source: Real transaction data from The Bread Basket
Period: October 30, 2016 - December 3, 2016
Transactions: 9,684 unique transactions
Records: 20,507 item entries
Columns: Transaction ID, Item, DateTime, Period of Day, Weekday/Weekend
Business Objectives:

Discover which products are frequently bought together
Identify high-value bundling opportunities
Detect negative associations to avoid ineffective promotions
Provide actionable recommendations for store layout and marketing
