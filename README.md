# 📦 Supply Chain Optimization Dashboard

> 🚀 **An End-to-End Supply Chain Data Analytics Project focused on optimizing inventory management, logistics performance, shipment efficiency, and business decision-making through interactive dashboards and data-driven insights.**

---

# 🌟 Project Overview

This project delivers a comprehensive Supply Chain Data Analytics solution designed to evaluate business performance, identify operational bottlenecks, and recommend strategies for improving supply chain efficiency.

Working as a **Supply Chain Data Analyst**, the project investigates real-world business challenges related to inventory management, customer demand, shipping operations, and warehouse performance. The analysis transforms raw business data into actionable insights using advanced analytics techniques and interactive dashboards.

The final dashboard enables business stakeholders to monitor critical Key Performance Indicators (KPIs), evaluate operational efficiency, and make informed strategic decisions.

---

# 🎯 Project Objectives

The primary goal of this project is to optimize supply chain operations by leveraging data analytics and business intelligence.

### The project focuses on:

✅ Evaluating overall business performance

✅ Monitoring sales, profit, and customer demand

✅ Understanding customer purchasing behavior

✅ Identifying high-performing products and departments

✅ Optimizing warehouse inventory management

✅ Analyzing shipping efficiency and delivery performance

✅ Detecting operational inefficiencies

✅ Delivering actionable recommendations for business improvement

---

# 🛠️ Project Methodology

A structured analytical workflow was followed to ensure accurate analysis and reliable business recommendations.

## 📌 Business Requirement

Design an interactive analytics dashboard capable of monitoring supply chain performance, identifying inefficiencies, and supporting business decision-making across multiple operational areas.

## 📊 Analytical Approach

The project combines three analytical techniques:

### 📈 Descriptive Analytics

Summarizes historical business performance and operational KPIs.

### 🔍 Exploratory Data Analysis (EDA)

Discovers trends, patterns, anomalies, and relationships hidden within the data.

### 🧩 Diagnostic Analytics

Investigates the root causes behind operational issues affecting supply chain performance.

---

# 💻 Technology Stack

The project was developed using the following technologies:

## 🐍 Python

Python was used for:

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Inventory Segmentation
- Business KPI Calculations

---

## 📊 Power BI

Power BI was used to:

- Build Interactive Dashboards
- Visualize Business KPIs
- Track Operational Performance
- Create Executive-Level Business Reports

---

# 📊 Dashboard Modules

The dashboard has been designed to support multiple business departments.

---

## 💼 Sales Performance Dashboard

Provides business leaders with a complete overview of sales performance and customer demand.

### Key Metrics

- 💰 Total Sales
- 📈 Net Sales
- 💵 Total Profit
- 📊 Profit Margin
- 🛒 Total Orders
- 👥 Customer Count
- 🏆 Best-Selling Products
- 📅 Sales Trend Analysis

---

## 📦 Inventory Management Dashboard

Helps inventory managers monitor warehouse operations and stock availability.

### Key Metrics

- 📦 Warehouse Inventory
- 🏢 Inventory Levels
- 💲 Storage Costs
- ✅ Order Fulfillment
- 📍 Product Availability
- 📊 Inventory Distribution
- 📈 Warehouse Performance

---

## 🚚 Shipping Performance Dashboard

Analyzes logistics operations and shipping efficiency.

### Key Metrics

- 🚛 Shipping Time
- ⏱️ Delivery Delay
- 📬 Shipping Modes
- 🌍 Warehouse Distribution
- 📦 Delivery Performance
- ⚠️ Late Shipment Rate
- 🗺️ Regional Shipping Analysis

---

# 🗂️ Dataset Overview

The project integrates **three interconnected datasets**, each representing a different stage of the supply chain lifecycle.

---

## 📋 Orders & Shipment Dataset

Contains customer purchasing and shipping information, including:

- 👤 Customer Details
- 🛒 Order Information
- 📦 Product Details
- 💲 Order Value
- 📅 Order & Shipping Dates
- 🚚 Shipping Methods

---

## 🏬 Inventory Dataset

Maintains warehouse inventory information, including:

- 📦 Product Inventory
- 📍 Warehouse Locations
- 📊 Inventory Quantity
- 💰 Inventory Cost
- 🏢 Storage Cost
- 📅 Monthly Inventory Status

---

## 📑 Fulfillment Dataset

Tracks order fulfillment and warehouse processing activities.

Includes:

- ✅ Order Fulfillment
- 🚚 Delivery Processing
- 🏬 Warehouse Operations
- 🔄 Inventory Movement
- 📦 Product Availability

---

# 📌 Business Outcome

By integrating these datasets, the project delivers a complete view of the supply chain—from customer orders and inventory management to warehouse operations and shipping performance.

The resulting insights empower decision-makers to identify operational bottlenecks, optimize inventory, improve delivery efficiency, reduce costs, and strengthen overall supply chain performance.
# 🧹 Data Preprocessing

High-quality data is essential for generating reliable business insights. Before beginning the analysis, the datasets were carefully examined, validated, and transformed to ensure consistency and accuracy.

The preprocessing phase focused on understanding the structure of each dataset, resolving data quality issues, and preparing the information for advanced analytics.

---

# 📂 Data Understanding

The project consists of three interconnected datasets representing different stages of the supply chain process.

## 👤 Customer Information

Includes customer-related details such as:

- Customer Identifier
- Customer Address
- Country
- Market Region

These attributes help analyze customer distribution, purchasing behavior, and regional demand.

---

## 🛒 Order Information

Contains transactional details, including:

- Order Date
- Ordered Products
- Quantity Ordered
- Gross Sales
- Discount Applied
- Order Value

This dataset forms the foundation for evaluating business performance and customer demand.

---

## 🚚 Shipment Information

Provides logistics-related details, including:

- Shipment Date
- Shipping Mode
- Scheduled Delivery
- Delivery Status

These fields are used to measure shipping efficiency and identify delays.

---

## 📦 Product Information

Includes detailed information about each product:

- Product Name
- Product Category
- Product Department

These attributes support product performance analysis and profitability evaluation.

---

## 🏬 Warehouse Inventory

Contains warehouse management information such as:

- Inventory Quantity
- Warehouse Location
- Inventory Cost
- Storage Cost
- Order Fulfillment

This dataset enables inventory monitoring and warehouse performance analysis.

---

# 🧹 Data Cleaning

Several preprocessing techniques were applied to improve data quality before conducting analysis.

## ✅ Removed Unnecessary Columns

Columns that did not contribute to the analysis were excluded to simplify the dataset.

Examples include:

- Order Item ID
- Order Time

Removing redundant information improved processing efficiency and reduced unnecessary complexity.

---

## 🔄 Corrected Data Types

Several columns contained incorrect data types.

The following conversions were performed:

- Date columns converted into DateTime format
- Numerical values converted to appropriate numeric types
- Categorical variables standardized for analysis

This ensured accurate calculations and reliable visualizations.

---

## 🌍 Standardized Customer Country

The **Customer Country** field contained inconsistent formatting and special characters.

To improve consistency:

- Removed unnecessary symbols
- Corrected formatting issues
- Standardized country names

This enhanced geographical analysis and market segmentation.

---

## 🔍 Missing Value Analysis

The datasets were thoroughly examined for missing values.

The analysis included:

- Detecting incomplete records
- Assessing their impact
- Applying appropriate handling techniques where required

This ensured that business insights were not influenced by incomplete information.

---

## 📑 Duplicate Record Verification

Duplicate observations were identified and reviewed to prevent inaccurate calculations.

Each duplicate entry was carefully evaluated before removal to preserve data integrity.

---

# ⚠️ Data Quality Challenges

During preprocessing, several business-specific inconsistencies were identified that required deeper investigation.

---

## 📦 Product Name Inconsistency

A mismatch was discovered between the **Orders Dataset** and the **Inventory Dataset**.

### Observation

Five product names existed within warehouse inventory but never appeared in customer orders.

This indicates that these products remained in inventory despite having no recorded customer demand.

### Decision

Instead of removing these products, they were retained because they contributed significantly to overall storage costs.

Keeping these records provided a more realistic representation of warehouse expenses and inventory utilization.

---

## 🚚 Invalid Shipping Time

Shipping duration was calculated as:

**Shipping Time = Shipment Date − Order Date**

During validation, two major issues were identified:

### Negative Shipping Time

Some records showed shipment dates occurring before order dates.

These values were considered recording errors and therefore removed.

---

### Unusually Long Shipping Duration

Certain shipments exceeded realistic delivery expectations.

Considering typical shipping standards:

- Domestic deliveries generally require **2–7 business days**
- International deliveries typically range between **1–4 weeks**

Any shipment duration:

- Less than **0 days**
- Greater than **28 days**

was treated as an outlier and excluded from further analysis.

This improved the reliability of shipping performance metrics.

---

# ⚙️ Feature Engineering

Several new business features were created to enrich the dataset and enable deeper analytical insights.

---

## 📅 Date Features

Separate date attributes were merged into a unified **DateTime** feature to simplify time-series analysis and trend visualization.

---

## 🚛 Shipment Status

A shipment status indicator was introduced to classify deliveries as either:

- ✅ On-Time
- ⚠️ Late Shipment

This classification supports logistics performance monitoring.

---

## ⏱️ Shipping Time

A new metric was calculated:

**Shipping Time = Shipment Date − Order Date**

This measures the actual delivery duration for every customer order.

---

## 📉 Delay Shipment Indicator

Shipment performance was further evaluated by comparing:

- Scheduled Delivery Time
- Actual Shipping Time

Orders exceeding the scheduled duration were labeled as **Late Shipments**, while the remaining orders were marked as **On-Time Deliveries**.

---

## 📊 Late Shipment Rate

A key logistics KPI was introduced:

**Late Shipment Rate = Total Late Shipments ÷ Total Orders**

This metric measures the overall efficiency of the delivery system and highlights potential operational bottlenecks.

---

# 💰 Business Performance Metrics

Several additional KPIs were engineered to evaluate financial performance more effectively.

---

## 💵 Net Sales

Calculated using:

**Net Sales = Gross Sales − (Discount × Gross Sales)**

This represents the company's actual revenue after discounts.

---

## 🏷️ Unit Price

Calculated as:

**Unit Price = Gross Sales ÷ Order Quantity**

This metric helps analyze pricing behavior across products.

---

## 📈 Profit Margin

Calculated using:

**Profit Margin = Total Profit ÷ Total Net Sales**

This KPI measures overall business profitability.

---

## 🏬 Storage Cost

Storage Cost was estimated as:

**Storage Cost = Inventory Cost per Unit × Warehouse Inventory**

This metric enables evaluation of warehouse expenses and inventory optimization opportunities.

---

# ✅ Outcome of Data Preparation

After completing preprocessing and feature engineering, the datasets became clean, consistent, and analysis-ready.

The refined data now supports:

- 📊 Accurate business performance evaluation
- 📦 Inventory optimization analysis
- 🚚 Shipping efficiency assessment
- 👥 Customer behavior analysis
- 💰 Profitability measurement
- 📈 Interactive dashboard development
- 🎯 Strategic decision-making based on reliable insights
- # 📊 Exploratory Data Analysis (EDA)

Once the datasets were cleaned and transformed, an extensive Exploratory Data Analysis (EDA) was performed to uncover meaningful insights, identify business trends, and evaluate the overall health of the company's supply chain operations.

The primary objective of this phase was to understand historical business performance, customer purchasing patterns, inventory utilization, and shipping efficiency while identifying operational challenges affecting business growth.

The analysis was organized into five major business areas:

- 💰 Business Performance
- 👥 Customer Analysis
- 📦 Product Analysis
- 🏬 Inventory Analysis
- 🚚 Shipping & Logistics Analysis

---

# 💰 Business Performance Analysis

This section focuses on evaluating the company's financial health and operational growth over time.

### 📌 Business Questions Investigated

- What are the company's total Net Sales, Profit, and Profit Margin?
- How do monthly Net Sales and Profit fluctuate?
- How has business performance changed over time?
- What trends can be observed in customer orders?
- How do Average Order Quantity and Unit Price vary across different periods?
- Which product departments contribute the most to sales and revenue?

### 📈 Key Performance Indicators (KPIs)

- 💵 Total Net Sales
- 📈 Total Profit
- 📊 Profit Margin
- 🛒 Total Orders
- 📅 Monthly Revenue Trend
- 💲 Average Unit Price
- 📦 Average Order Quantity

These KPIs provide a clear understanding of business performance and long-term revenue trends.

---

# 👥 Customer Analysis

Understanding customer behavior is essential for optimizing inventory planning and improving business strategies.

### 📌 Business Questions Investigated

- How are customers distributed across different countries and markets?
- How has the customer base evolved over time?
- Are there noticeable purchasing trends or seasonal buying patterns?
- Which markets contribute most significantly to business growth?

### 🔍 Customer Insights

The analysis focused on:

- 🌍 Customer Geographic Distribution
- 📈 Customer Growth Trends
- 🛒 Purchasing Behavior
- 🌎 Market Performance
- 📅 Demand Patterns

These insights help identify high-value customer segments and changing market dynamics.

---

# 📦 Product Performance Analysis

Product analysis evaluates customer preferences and identifies the products driving business growth.

### 📌 Business Questions Investigated

- Which product categories receive the highest customer demand?
- Which products generate the highest revenue?
- Which product departments contribute the most profit?
- What are the company's best-performing products?

### 📊 Product Metrics

The analysis includes:

- 🏆 Best-Selling Products
- 💰 Highest Revenue Products
- 📈 Most Profitable Categories
- 📦 Product Demand Distribution
- 🛍️ Department-Level Performance

Understanding product performance supports strategic inventory planning and product portfolio optimization.

---

# 🏬 Inventory Analysis

Inventory management plays a critical role in maintaining operational efficiency while minimizing storage costs.

### 📌 Business Questions Investigated

- Which departments account for the largest inventory volume?
- Which products generate the highest storage costs?
- How does warehouse inventory change over time?
- What is the average fulfillment rate?
- Which departments demonstrate the strongest inventory performance?

### 📊 Inventory Metrics

- 📦 Warehouse Inventory
- 🏢 Inventory Distribution
- 💰 Storage Cost
- 📈 Inventory Cost per Unit
- 🚚 Order Fulfillment Rate
- 📍 Warehouse Performance

This analysis helps identify opportunities for reducing unnecessary inventory while maintaining product availability.

---

# 🚚 Shipping & Logistics Analysis

Efficient logistics operations are essential for ensuring customer satisfaction and reducing operational costs.

### 📌 Business Questions Investigated

- Which warehouses handle the majority of shipments?
- Which shipping methods are most frequently selected?
- How does shipping time vary by delivery mode?
- What is the Late Shipment Rate across different markets?
- How has delivery performance changed over time?

### 📊 Logistics KPIs

- 🚛 Shipping Time
- ⚠️ Late Shipment Rate
- 📦 Shipping Mode Distribution
- 🌍 Warehouse Shipment Distribution
- 📈 Delivery Performance Trends

These metrics provide valuable insights into logistics efficiency and delivery reliability.

---

# 🔍 Key Findings

Following a comprehensive analysis of business operations, several significant observations were identified.

## 💰 Strong Historical Business Performance

Over the three-year analysis period, the company achieved impressive financial results, generating approximately **$5.5 million in Net Sales** and nearly **$4 million in Profit**.

This resulted in an overall **Profit Margin of approximately 72%**, indicating strong profitability despite operational challenges.

---

## 📉 Declining Revenue and Order Volume

Although the company performed consistently for most of the observed period, a sharp decline in orders was detected during the later stages of the analysis.

This decrease directly impacted:

- Net Sales
- Profit
- Customer Orders

Interestingly, revenue and profit declined at almost identical rates, suggesting that operational costs remained relatively stable while revenue generation weakened considerably.

This indicates that the primary issue originated from reduced business activity rather than increased operational expenses.

---

## 🛍️ Decline of Core Product Departments

Further investigation revealed that several historically high-performing departments—including Apparel, Fan Shop, Footwear, and Golf—experienced a significant reduction in sales.

Since these departments previously contributed the majority of business revenue, their decline had a substantial impact on overall company performance.

---

## 👥 Changing Customer Demand

Customer purchasing behavior evolved throughout the analysis period.

Although customer demographics shifted across different markets, overall purchasing demand remained relatively stable.

This suggests that changes in customer preferences alone cannot fully explain the company's declining financial performance.

---

## 📦 Inventory Trends

Warehouse inventory and storage costs declined alongside business revenue.

This observation suggests that the company may have experienced supply disruptions affecting product availability rather than intentionally reducing inventory.

Additionally, newly introduced product categories gradually replaced several traditional best-selling products.

---

## 🚚 Shipping Performance Issues

Shipping analysis revealed persistent operational inefficiencies.

Several orders selected for premium shipping services—such as Same Day and First Class Delivery—were delivered significantly later than expected.

This indicates weaknesses within the company's logistics and fulfillment processes.

---

## ⚠️ High Late Shipment Rate

One of the most critical findings was the consistently high Late Shipment Rate.

Approximately **40% of all orders** experienced delivery delays throughout the analysis period.

Since this trend remained consistent across different markets and product departments, it suggests that the issue is systemic rather than location-specific.

Improving logistics operations should therefore become a major business priority.

---

# 📌 Summary of Business Insights

The Exploratory Data Analysis demonstrates that the company remains fundamentally profitable but faces several operational challenges that threaten long-term growth.

The most significant issues identified include:

- 📉 Declining sales from historically high-performing product categories.
- 📦 Possible supply chain disruptions affecting inventory availability.
- 🚚 Inefficient shipping and fulfillment operations.
- ⚠️ Consistently high late shipment rates.
- 📊 Opportunities to optimize inventory management and warehouse operations.

These findings serve as the foundation for the next stage of the project, where root causes are investigated through hypothesis analysis and inventory segmentation.
# 🌳 Root Cause Analysis

Following the Exploratory Data Analysis (EDA), a structured Root Cause Analysis was conducted to determine the underlying factors responsible for the decline in business performance and supply chain efficiency.

Instead of focusing solely on individual metrics, the analysis examined the complete supply chain ecosystem—from suppliers to customers—to identify the most probable causes of operational challenges.

To structure the investigation, the **SCQ Framework (Situation–Complication–Question)** was applied.

---

# 📖 SCQ Framework

## 🟢 Situation

Between **2015 and Q3 2017**, the company maintained stable revenue growth and strong profitability.

The majority of its revenue originated from several high-performing product departments, particularly:

- 👕 Apparel
- ⛳ Golf
- 🏪 Fan Shop
- 👟 Footwear

These departments consistently generated the highest sales and played a major role in sustaining business growth.

---

## 🟠 Complication

Beginning in **Q4 2017**, the business experienced a sudden decline in revenue, order volume, and profitability.

Several previously high-performing product categories almost disappeared from customer orders.

At the same time:

- 📉 Revenue decreased significantly
- 📦 Inventory levels dropped
- 💰 Storage costs declined
- 🚚 Shipping inefficiencies persisted

These changes indicated that the problem extended beyond customer demand and pointed toward broader supply chain issues.

---

## ❓ Business Question

The key business challenge became:

> **How can the company restore revenue growth while improving supply chain efficiency and preventing similar operational disruptions in the future?**

Answering this question required identifying the true root causes behind the company's declining performance.

---

# 🌍 Understanding the Supply Chain

To investigate the problem, the entire supply chain process was divided into three interconnected stages.

---

## 🏭 Stage 1 — Suppliers

Suppliers provide products that the company later sells to customers.

This stage includes:

- Supplier Relationships
- Manufacturing
- Product Availability
- Order Fulfillment
- Delivery to Warehouses

Supplier performance directly influences inventory availability and business continuity.

One important KPI evaluated during this stage was:

✅ Average Order Fulfillment

---

## 🏬 Stage 2 — Warehouse & Inventory

Once products arrive from suppliers, they are stored within warehouses before customer orders are processed.

Warehouse operations include:

- Inventory Management
- Storage Allocation
- Inventory Monitoring
- Reorder Planning
- Warehouse Costs

The following KPIs were analyzed:

- 📦 Warehouse Inventory
- 💰 Storage Cost
- 🏢 Warehouse Location
- 📈 Inventory Utilization

Efficient inventory management helps reduce stock shortages while avoiding excessive inventory costs.

---

## 🚚 Stage 3 — Order Fulfillment & Shipping

After customers place orders, warehouse teams prepare products for shipment.

This stage involves:

- Order Verification
- Product Picking
- Packaging
- Shipping
- Customer Delivery

Key logistics metrics analyzed include:

- 🚛 Shipping Time
- ⚠️ Late Shipment Rate
- 📦 Delivery Performance

Although information regarding returns and cancelled orders was unavailable, shipment delays provided valuable insight into operational efficiency.

---

# 📈 Demand Forecasting

An effective supply chain depends on accurate demand forecasting.

Historical sales trends, customer purchasing behavior, and market demand all contribute to forecasting future inventory requirements.

Proper demand forecasting enables organizations to:

- 📦 Reduce Stockouts
- 💰 Lower Storage Costs
- 📈 Improve Inventory Planning
- 🚚 Increase Supply Chain Efficiency

Demand forecasting therefore became an important consideration throughout the analysis.

---

# 🌳 Hypothesis Issue Tree

Based on the findings from the EDA, the investigation was divided into **External Factors** and **Internal Factors**.

This approach helped identify the most likely causes of declining business performance.

---

# 🌍 External Factors

External factors represent influences outside the company's direct control.

## 👥 Hypothesis 1 — Customer Preferences Changed

One possibility is that customer purchasing behavior shifted over time.

Potential reasons include:

- New market trends
- Seasonal demand
- Product preference changes
- Emerging competitors

Although customer distribution changed throughout the analysis period, overall purchasing demand remained relatively stable.

Therefore, customer preference alone was unlikely to explain the sudden business decline.

---

## 🏭 Hypothesis 2 — Supplier Disruptions

Another possibility is that suppliers experienced disruptions affecting product availability.

Potential causes include:

- Manufacturing delays
- Supply shortages
- Transportation disruptions
- Vendor reliability issues

Since inventory levels declined shortly before revenue dropped, supplier disruptions appeared to be a highly probable explanation.

---

# 🏢 Internal Factors

Internal factors relate directly to company operations.

---

## 📦 Hypothesis 3 — Product Portfolio Changes

Another possibility is that the company intentionally modified its product offerings.

This could occur because of:

- Business restructuring
- Product lifecycle management
- Introduction of new product categories
- Market testing strategies

However, completely removing historically successful product categories without a gradual transition would represent a significant business risk.

Therefore, this hypothesis requires additional investigation.

---

## 🚚 Hypothesis 4 — Delivery Performance Reduced Customer Loyalty

Persistent shipping delays may have negatively impacted customer satisfaction.

Possible consequences include:

- Customer dissatisfaction
- Lower retention rates
- Reduced repeat purchases
- Migration to competing businesses

Although delivery delays remained consistently high, customer numbers only declined significantly during Q4 2017.

This suggests that shipping delays alone were unlikely to be the primary cause of declining revenue.

---

# 📊 Inventory Segmentation Strategy

The company manages more than **50 product categories** and over **100 individual products**.

Analyzing every product independently would make decision-making inefficient.

To simplify the analysis, an **ABC–XYZ Inventory Segmentation** model was implemented.

This approach classifies inventory according to:

- 💰 Revenue Contribution
- 📈 Demand Stability

The segmentation allows inventory decisions to be prioritized based on business value and demand patterns.

---

# 📦 ABC Analysis

ABC Analysis categorizes products according to their contribution to total Net Sales.

### 🥇 Category A — High Business Value

Products contributing approximately **80% of total Net Sales**.

These items represent the company's most valuable inventory and require the highest management priority.

---

### 🥈 Category B — Medium Business Value

Products contributing roughly **15% of remaining sales**.

These products generate moderate revenue and require regular inventory monitoring.

---

### 🥉 Category C — Low Business Value

Products contributing the final **5% of Net Sales**.

These items have relatively low financial impact and can be managed with lower inventory priority.

---

# 📈 XYZ Analysis

XYZ Analysis evaluates inventory based on demand variability using the **Coefficient of Variation (CV).**

### 🟢 X Category — Stable Demand

Products with:

**CV < 0.25**

Demand is consistent and highly predictable.

---

### 🟡 Y Category — Moderate Demand Variability

Products with:

**0.25 ≤ CV ≤ 0.50**

Demand changes due to seasonal or market trends.

---

### 🔴 Z Category — Highly Irregular Demand

Products with:

**CV > 0.50**

Demand is unpredictable and requires cautious inventory planning.

---

# 📌 Data Validation During Segmentation

During segmentation, five inventory products were identified that appeared in warehouse records but had no corresponding customer orders.

Instead of immediately removing these records, a detailed investigation was conducted.

Although these products generated no recorded sales, warehouse inventory continued to fluctuate over time, suggesting they remained operational inventory.

The most likely explanation was incomplete transaction recording rather than inactive inventory.

To avoid biasing the segmentation analysis, these products were excluded only during the inventory classification stage, while all previous business analyses remained unaffected.

This ensured that warehouse cost analysis, inventory trends, and supply chain insights accurately reflected actual business operations.
# 📊 Exploratory Data Analysis – Phase II

After completing the initial business analysis, a second round of exploratory analysis was conducted using the **ABC–XYZ Inventory Segmentation Model**. This phase focused on understanding inventory behavior, evaluating demand variability, and validating the hypotheses identified during the root cause analysis.

The objective was to determine how inventory management practices influenced supply chain performance and overall business outcomes.

---

# 📦 Inventory Segmentation Insights

The ABC–XYZ classification revealed several important patterns regarding inventory value, demand consistency, and warehouse utilization.

## 📈 Shift in Inventory Composition

A gradual transition was observed from traditional high-performing inventory segments toward newly introduced products.

Although both **XA** and **YA** segments represented the company's primary revenue sources, their purchasing patterns differed considerably.

### XA Segment

- 💰 High product value
- 📦 Lower order quantity
- 📈 Strong revenue contribution
- 🎯 Premium inventory

---

### YA Segment

- 💵 Moderate product value
- 📦 Larger purchase quantities
- 📈 Consistent customer demand
- 🛒 High order frequency

---

### XB & XC Segments

These emerging inventory segments demonstrated promising growth potential.

Although their overall contribution remained lower than XA and YA, they gradually became increasingly important after the decline of traditional best-selling products.

This suggests a possible shift in customer demand or product availability.

---

# 🏬 Overstock & Inventory Utilization

Inventory analysis revealed recurring periods of excessive stock levels.

While maintaining safety stock is an essential inventory strategy, several products consistently exceeded expected demand.

In some periods, warehouse inventory exceeded actual customer demand by approximately **30%**, leading to:

- 💰 Increased storage costs
- 📦 Excess warehouse occupancy
- 📉 Reduced inventory turnover
- ⚠️ Higher operational expenses

These findings highlight opportunities to optimize inventory planning and warehouse utilization.

---

# 🚚 Shipping Performance

Further logistics analysis showed that delayed shipments were not strongly associated with supplier fulfillment times.

Instead, delays appeared to occur after products had already reached company warehouses.

This indicates that the primary bottleneck exists within the company's internal delivery and distribution processes.

Because similar delay patterns were observed across multiple geographic regions, the issue appears to be systemic rather than location-specific.

---

# 🧪 Hypothesis Validation

Each hypothesis identified during the Root Cause Analysis was evaluated using supporting evidence from the data.

---

## ✅ Hypothesis 1 — Customer Preferences Changed

### Finding

Customer purchasing behavior evolved over time; however, the decline in revenue occurred before any major reduction in customer demand.

### Conclusion

❌ **Not Supported**

Changes in customer preferences alone cannot fully explain the company's declining business performance.

---

## ✅ Hypothesis 2 — Supplier Disruptions

### Finding

Inventory shortages appeared before the decline in customer orders.

Several high-performing inventory segments experienced abrupt reductions in availability.

### Conclusion

✅ **Strongly Supported**

Supplier disruptions are the most probable root cause of the company's operational decline.

The organization likely experienced interruptions within its supply network, reducing the availability of high-demand products.

---

## ✅ Hypothesis 3 — Product Portfolio Changes

### Finding

The company introduced several new products while older high-performing products disappeared.

However, completely removing products responsible for approximately **80% of total revenue** without a gradual transition would represent a highly risky business decision.

### Conclusion

⚠️ **Partially Supported**

Although product offerings changed, available evidence suggests these changes were more likely a consequence of supply issues rather than a planned strategic decision.

Long-term business data would be required for complete validation.

---

## ✅ Hypothesis 4 — Shipping Delays Reduced Customer Loyalty

### Finding

Late shipment rates remained consistently high throughout the analysis period.

However, customer numbers declined significantly only during Q4 2017.

### Conclusion

⚠️ **Partially Supported**

Shipping delays negatively affect customer satisfaction but were unlikely to be the primary cause of declining revenue.

Instead, delivery inefficiencies should be viewed as an operational weakness requiring improvement.

---

# 💡 Business Recommendations

Based on the analytical findings, several strategic recommendations are proposed to improve supply chain performance and support long-term business growth.

---

## 🥇 Restore High-Value Inventory Segments (XA & YA)

Historical analysis indicates that XA and YA products generated the majority of company revenue.

Recommended actions include:

- 🤝 Establish alternative supplier partnerships
- 🌍 Diversify sourcing locations
- 📦 Improve supplier risk management
- 🔄 Strengthen procurement planning
- 📈 Monitor supplier performance continuously

Restoring these inventory segments should be considered the organization's highest priority.

---

## 🚀 Expand High-Potential Products (XB & XC)

Emerging inventory segments demonstrated encouraging growth after the decline of traditional best-selling products.

Recommendations include:

- 📊 Conduct market research
- 📈 Forecast future demand
- 🎯 Expand successful product lines
- 🌎 Identify new market opportunities

These products may become future revenue drivers.

---

## 📉 Optimize Low-Value Inventory

Segments such as:

- YB
- YC
- ZB
- ZC

contribute relatively little to overall revenue while increasing storage costs.

Recommended actions:

- 📦 Reduce inventory levels
- 💰 Minimize warehouse costs
- 🔄 Eliminate obsolete products where appropriate

This improves inventory efficiency without significantly impacting sales.

---

# 📈 Improve Demand Forecasting

Demand forecasting should become a core component of inventory planning.

Recommended strategies include:

- 📊 Analyze historical sales trends
- 🤖 Implement predictive analytics models
- 📅 Monitor seasonal demand
- 📦 Define inventory reorder points
- 🛡️ Maintain optimized safety stock

Accurate forecasting reduces both stock shortages and excessive inventory.

---

# 🏬 Optimize Warehouse Operations

Warehouse performance can be improved by:

- 📍 Optimizing inventory allocation
- 🚚 Redesigning warehouse workflows
- 📦 Improving inventory visibility
- 📊 Monitoring warehouse KPIs continuously

These improvements help reduce operational costs while increasing efficiency.

---

# 🚛 Strengthen Logistics & Delivery Performance

The consistently high Late Shipment Rate indicates opportunities for logistics optimization.

Recommended initiatives include:

- 🛣️ Optimize transportation routes
- 🚚 Improve delivery scheduling
- 🤝 Collaborate with regional logistics partners
- 🌏 Establish additional distribution hubs
- 📍 Expand warehouse coverage for international markets

A strategically located warehouse in Asia, for example, could significantly improve delivery performance for regional customers.

---

# 🎯 Project Outcomes

Through comprehensive data analysis, this project successfully:

✅ Evaluated overall business performance.

✅ Identified operational inefficiencies across the supply chain.

✅ Measured inventory utilization and storage costs.

✅ Assessed shipping efficiency and delivery performance.

✅ Investigated customer purchasing behavior.

✅ Validated multiple business hypotheses using analytical evidence.

✅ Applied the ABC–XYZ Inventory Segmentation framework.

✅ Delivered actionable recommendations for supply chain optimization.

---

# 🚀 Future Enhancements

Potential future improvements include:

- 🤖 Machine Learning-based Demand Forecasting
- 📈 Predictive Inventory Optimization
- 🚚 Route Optimization Algorithms
- 🌍 Real-Time Supply Chain Monitoring
- 📊 Automated Executive Dashboards
- ☁️ Cloud-Based Business Intelligence Solutions

These enhancements would enable proactive decision-making and improve long-term operational resilience.

---

# 🏁 Conclusion

This project demonstrates how data analytics can be leveraged to transform complex supply chain data into meaningful business insights.

By combining data preprocessing, feature engineering, exploratory analysis, inventory segmentation, and interactive dashboard development, the project provides a comprehensive understanding of operational performance and identifies practical strategies for improving supply chain efficiency.

The findings emphasize the importance of supplier reliability, inventory optimization, demand forecasting, and logistics performance in building a resilient and efficient supply chain.

Ultimately, this project showcases how business intelligence and data-driven decision-making can support sustainable operational improvement and long-term organizational success.

---

# 🙏 Acknowledgements

This project was developed for educational and portfolio purposes using publicly available supply chain datasets.

Special thanks to the open-source community and data analytics resources that inspired the analytical methodology and business intelligence approach adopted throughout this project.

---

## ⭐ If you found this project useful, consider giving the repository a star!
