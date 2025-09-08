# airbnb-data-engineering
End-to-end Airbnb data engineering project with Delta Live Tables, Databricks SQL dashboards, and Genie Data Room.

# Airbnb Operational Efficiency and Guest Experience

This assignment implements an end-to-end data pipeline and analytics workflow for Airbnb using Databricks.  

---

## ⚙️ Workflow
1. **Data Generation**
   - Created synthetic Airbnb datasets for properties, bookings, reviews, and revenue.

2. **Delta Live Tables (DLT)**
   - Built bronze → silver → gold pipeline.
   - Computed operational metrics:
     - Average Booking Value  
     - Guest Satisfaction Score  
     - Repeat Booking Rate  
     - Cancellation Rate  
     - Active Properties Count  
     - Revenue per Property  
     - Maintenance Cost per Property  
     - Review Sentiment Score  

3. **Dashboard (Databricks SQL)**
   - Built visualizations for KPIs:
     - Counter widgets (for % metrics).  
     - Bar charts (for revenue & maintenance).  
     - Line chart (for sentiment trend).  

4. **Genie Data Room**
   - Connected gold & silver KPI tables.
   - Enabled natural-language queries like:
     - “What is the average booking value?”
     - “What is the status distribution of active properties?”
     - “What is the average repeat booking rate?”

---

## Outcome
- End-to-end Airbnb data pipeline running in Databricks.  
- Operational dashboard with KPIs.  
- Genie space for ad-hoc exploration.  

