📱 PhonePe Pulse Data Visualization Dashboard
A comprehensive interactive dashboard and analysis platform built using Streamlit, Pandas, and Plotly, based on PhonePe Pulse datasets. This project visualizes digital transaction trends across India using maps, charts, EDA, and SQL-based case studies.

📌 Project Highlights
📂 9 curated datasets from PhonePe Pulse

📊 Interactive visualizations (Bar, Line, Pie, Scatter)

🧭 Geo visualizations focused on Indian districts

🔍 EDA insights with pre-rendered plots

🧠 SQL case studies with visual output

☁️ Deployed on Streamlit Community Cloud (Free)

🗃️ Datasets Used
The app includes all major categories from the PhonePe Pulse dataset:

Dataset Category	Description
Aggregated Transaction	Transaction volume and amount by state/year/quarter
Aggregated User	Registered and app-open users aggregated by geography
Aggregated Insurance	Insurance transaction stats aggregated by region
Map Transaction	District-level transaction mapping with coordinates
Map User	District-level user engagement
Map Insurance	District-wise insurance activity
Top Transaction	Top-performing districts by transaction volume
Top User	Districts with highest user engagement
Top Insurance	Districts with highest insurance volumes

📌 Features Covered
🧭 Sidebar Filters
State, Year, Quarter filters (dynamically shown)

Dataset selector for all 9 datasets

📊 Dashboard Tab
Bar, Line, Scatter, Pie charts

Dynamic charting based on user inputs

Auto detection of categorical and numerical columns

🔍 EDA Tab
Pre-rendered PNG plots shown dynamically

Visual insights into trends and outliers

🧠 SQL Case Studies Tab
CSV result viewer

Matching visual representation if available (PNG)

🗺️ Geo Visualization Tab
District-wise scatter plots on India-only map

Bubble size based on metrics like users, transactions, or amount

Uses Plotly's scatter_geo() with India bounds

🛠️ Tech Stack
Streamlit – UI Framework

Plotly – For interactive graphs

Pandas – Data manipulation

Python – Core programming

🚀 Deployment (Free)
Check Out the Streamlt Dashboard : https://phonepe-project-5mmjvkmjkvtbf2eqnar5ke.streamlit.app/
