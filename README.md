## **Sales Analytics Dashboard using Python \& Dash**


Project Overview:
---



This project is an interactive Sales Analytics Dashboard built using Python, Dash, and Plotly.
It analyzes sales data to provide insights into revenue, product performance, and customer trends.
---

##### The dashboard helps businesses make data-driven decisions by visualizing key sales metrics.



## Project Workflow:


Data Generation / Collection
Data Cleaning
Data Transformation
Feature Engineering (Revenue calculation)
Data Visualization
Dashboard Development
---


Project Structure:
---


sales\_dashboard/
│
├── sales\_data.csv
├── generate\_data.py
├── dashboard.py
├── requirements.txt
└── README.md
---


Dataset:
---


Synthetic dataset generated using Python
Contains sales-related information such as:
Order ID
Product
Category
Quantity
Price
City
---

##### Date


Derived column:
Revenue = Quantity × Price
---


Data Preprocessing:
---

##### Converted Date column to datetime format


Created new feature:
---

##### Revenue calculation


Grouped data for analysis:
Product-wise sales
Category-wise revenue
Date-wise trends
---


Dashboard Features:
---


City-based filtering
Total Revenue calculation
Top Products analysis
Category-wise revenue distribution
Sales trend over time
---


Technologies Used:
---


Python
Pandas
Plotly
Dash
---


How to Run:
---


Clone the repository
---


Install dependencies:
---


pip install pandas dash plotly
---


Run the dashboard:
---


python dashboard.py
---


Open in browser:
---


http://127.0.0.1:8050
---


Example Insights:
---


Identify top-selling products
Analyze revenue by category
Track sales trends over time
Compare performance across cities
---


Project Highlights:
---


Beginner-friendly data analytics project
Interactive dashboard using Dash
Real-world business use case
Clean and simple UI for visualization
---


Future Improvements:
---


Add SQL database integration
Add authentication system
Deploy dashboard online
Add advanced filters (date range, product category)
Use real-world datasets
---


Author:
---

##### Sales Dashboard Project by Chithukati Sindhupriya

