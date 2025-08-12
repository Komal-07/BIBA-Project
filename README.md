# BIBA-Project
This project is based on TechTronix Ltd: Optimization for Customer Retention and Revenue Growth

--

This project designs and implements a **CRM + BI solution** for **TechTronix Ltd**, a smart home device company, to **reduce churn, boost revenue, and enhance customer experience**.  
By integrating **Salesforce CRM** with **Microsoft Power BI**, we built **predictive analytics, customer segmentation, and sentiment analysis dashboards** for actionable business insights.  
📄 *Developed as part of MSc Data Analytics – Business Intelligence & Business Analytics module (National College of Ireland).*  

--

This hypothetical company is facing some challenges in their business like High Cutomer Churn, Lack of personalization, Inconsistent followups, Absence of Strategic Upselling, and Sentiment Analysis Absent.

--

## 🎯 Business Goals  
✅ Reduce **customer churn** & increase repeat purchases  
✅ Deliver **personalized, sentiment-aware communication**  
✅ Improve **Customer Lifetime Value (CLTV)** via upselling & cross-selling  
✅ Provide **real-time KPIs** for decision-making  
✅ Integrate **sentiment scoring** into customer journey 

--

## 🛠️ Tech Stack  
| Tool | Purpose |
|------|---------|
| **Salesforce** | CRM platform for lead, contact & case management |
| **Power BI** | Interactive dashboards & real-time KPIs |
| **Python (Pandas, NumPy, Faker)** | Data generation, cleaning & preprocessing |
| **Matplotlib, Seaborn** | Exploratory Data Analysis (EDA) |
| **Sentiment Analysis** | Polarity scoring from customer feedback |

--

## Data Generation

To simulate realistic customer and sales data for the CRM and dashboard testing, we used **Python** in a **Jupyter Notebook** environment with libraries such as **Pandas**, **NumPy**, and **Faker**. Two synthetic datasets were created—`techtronix_scored`, and `techtronix_with_sentiment`—to represent the complete customer journey. The `Faker` library generated realistic names, emails, locations, and dates, while **custom logic** assigned purchase histories, lead sources, and sales stages. Sentiment scores were derived from randomly generated feedback text using basic polarity scoring techniques. All datasets were cleaned (removing duplicates, formatting dates, ensuring foreign key integrity) and exported as CSV files, which were then used for CRM import and **Power BI dashboard** development. This approach allowed us to validate the system design without relying on sensitive real-world data.

--

## CRM Implementation

In this project, **Salesforce CRM** was implemented as the backbone for managing TechTronix Ltd’s customer lifecycle—from lead acquisition to post-sales support. We configured lead, contact, opportunity, and case management modules to align with the company’s sales funnel, and integrated automated workflows to trigger follow-ups, retention campaigns, and sentiment-based escalation. Mock customer data generated in Python was imported into Salesforce, enabling realistic testing of lead scoring, churn prediction, and engagement tracking. This CRM setup ensured that sales, marketing, and support teams could operate from a single source of truth, while Power BI dashboards visualized Salesforce data in real time for monitoring KPIs like conversion rates, churn trends, and customer lifetime value.

--

## 📊 Dashboards  
1️⃣ **Customer Insights & Segmentation** – Cluster-based targeting, demographics, geo-mapping 
      This dashboard identifies and analyzes distinct customer groups based on purchase behavior, demographics, and location. Using cluster segmentation, it highlights high-value customers for retention campaigns, price-sensitive segments for targeted promotions, and underperforming regions for potential market development. Demographic breakdowns—such as age and gender—reveal key audience profiles, enabling personalized marketing strategies and informed product placement decisions. Geographical mapping supports region-specific campaigns and logistical planning.
 
2️⃣ **Sentiment Analysis & Feedback** – Sentiment vs churn, keyword insights, time-series trends  
      This dashboard transforms customer feedback into actionable insights using sentiment analysis. It visualizes how positive, neutral, or negative sentiments correlate with churn rates, helping prioritize retention strategies for dissatisfied customers. Keyword frequency analysis uncovers recurring issues or strengths—such as “delivery delays” or “product quality”—guiding process improvements. A time-series view of sentiment trends tracks customer satisfaction over months, allowing the business to spot emerging problems early and measure the impact of corrective actions.
      
3️⃣ **Sales & Conversion Funnel** – Stage drop-off analysis, revenue trends, campaign tracking  
      This dashboard provides end-to-end visibility of the sales pipeline, revealing where leads drop off at each stage (e.g., from Qualified to Proposal). By analyzing stage-by-stage revenue trends, it identifies bottlenecks, pricing issues, or sales process inefficiencies. Campaign performance metrics show how different marketing efforts contribute to lead conversion, enabling data-backed resource allocation. The funnel view also supports forecasting by showing the value and volume of deals in each stage, helping sales teams focus on high-impact opportunities.




