**AtliQ Mart Supply Chain Analysis**

📊 **Project Overview**

This project provides a comprehensive analysis of the supply chain and delivery performance for AtliQ Mart, a growing FMCG manufacturer. The primary objective was to diagnose the root causes of service issues, specifically focusing on the company's On-Time and In-Full (OTIF) delivery metrics. The analysis uses a Power BI dashboard to explore key performance indicators (KPIs) and identify specific bottlenecks, inconsistencies across different regions, customers, and product categories.
________________________________________
**Contents**

1. [Home View](https://github.com/sherinjthomas29/AtliQ-Mart-FMCG-Domain-Power-BI-Dashboard/blob/main/Home%20View.png)
2. Order [View](https://github.com/sherinjthomas29/AtliQ-Mart-FMCG-Domain-Power-BI-Dashboard/blob/main/Order%20View.png)
3. [Delivery View](https://github.com/sherinjthomas29/AtliQ-Mart-FMCG-Domain-Power-BI-Dashboard/blob/main/Delivery%20View.png)
4. [Performance View](https://github.com/sherinjthomas29/AtliQ-Mart-FMCG-Domain-Power-BI-Dashboard/blob/main/Performance%20View.png)
________________________________________
📈 **Key Insights**

Based on the analysis, the following key insights were identified:

**Critically Low OTIF Rate**: The overall On-Time and In-Full (OTIF) rate is a major concern at just 29%, indicating a significant gap in service delivery.

**Lead Time is the Primary Bottleneck**: The main issue is not the delivery transit time (Avg. 0.42 days), but the long internal processing time (Avg. Lead Time of 2.42 days), which is the primary cause of delivery delays.

**Inconsistent Performance**: Fulfillment rates vary widely across different dimensions:

**By City**: Vadodara is the weakest-performing city, while Surat has the highest on-time rate.

**By Customer**: Performance is highly inconsistent, with some customers like Propert Stores having a very low OTIF % while others perform much better.

**By Product**: There are critical stock and fulfillment issues with specific products, most notably AM Butter 100, which has an extremely low In-Full rate of 5.86%.
________________________________________
🛠️ **Tools & Methods**
   
**Tools**:

**Power BI Desktop**: Used for data cleaning, transformation, and creating interactive visualizations.

**DAX (Data Analysis Expressions)**: Utilized for creating custom measures and calculated columns to derive key metrics like OTIF%, Lead Time, and In-Full percentages.

**Methodology**:

**Data Sourcing**: Connecting to the provided dataset (assumed to be from AtliQ Mart's internal systems).

**Data Modeling**: Establishing relationships between various tables (e.g., Orders, Deliveries, Customers, Products) to enable cross-functional analysis.

**Dashboard Design**: Creating a three-view dashboard (Order View, Delivery View, and Performance View) to provide a logical flow from a high-level overview to granular, actionable insights.

**KPI Analysis**: Calculating and visualizing key performance indicators (KPIs) to identify gaps between actual performance and targets.

**Diagnostic Analysis**: Drilling down into the data to uncover root causes of poor performance, such as long lead times and product-specific fulfillment issues.
________________________________________
💡**Suggestions & Improvements**

The following recommendations are provided to help AtliQ Mart improve its supply chain efficiency:

**Streamline Warehouse Operations**: Focus on reducing the long lead time by optimizing internal processes, potentially through the use of a Warehouse Management System (WMS) or automation.

**Targeted Inventory Management**: Conduct a detailed root-cause analysis for high-failure products to identify and resolve stock availability issues. Implement specific inventory strategies for items with critically low In-Full rates.

**Implement City and Customer-Specific Strategies**: Develop tailored action plans for underperforming cities and customers. This could include revising logistics partnerships or addressing specific fulfillment requirements.

**Enhance Data Analytic**s: Use the current dashboard as a foundation to build predictive models for demand forecasting and implement real-time tracking to improve transparency and proactive problem-solving.
________________________________________
📝 **Conclusion**

This project successfully diagnosed the core supply chain challenges faced by AtliQ Mart, identifying that the long order processing lead time is the primary factor behind the low OTIF rate. The analysis provides actionable insights that can be used to develop targeted strategies for improving performance at the city, customer, and product levels. By addressing these key issues, AtliQ Mart can enhance its service quality and retain key customer contracts.
________________________________________
**Abbreviations**

**LIFR** : Line In Fill Rate,
 **VOFR** : Volume In Fill Rate,
 **OT**   : On Time Delivery,
 **IF**   : In Full Delivery,
 **OTIF** : On Time In Full Delivery
________________________________________
💻 **Presentation**

[Link](https://github.com/sherinjthomas29/AtliQ-Mart-FMCG-Domain-Power-BI-Dashboard/blob/main/Presentation.pdf)
_______________________________________
📈 **Live Dashboard**

[Link](https://app.powerbi.com/view?r=eyJrIjoiMmNkNWY2YzYtNjc0OC00NmUwLWJiOTctMjYzY2M0ZGNiNTA5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
