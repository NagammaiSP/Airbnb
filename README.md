# AirBnb-Analysis Streamlit App

Overview
This Streamlit application provides an interactive analysis of Airbnb data. It allows users to explore data through various filters and visualizations, including bar charts, pie charts, scatter plots, and maps.

Features
- Home: Overview of Airbnb's business model, impact on tourism, and project skills takeaway.
- Explore Data: Interactive data exploration with filters for neighborhood groups and neighborhoods. Visualizations include:
  - Bar charts for room type price distribution.
  - Pie charts for neighborhood group price distribution.
  - Scatter plots for room types across neighborhoods.
  - Data tables with downloadable CSV options.
  - Map view of Airbnb listings.
- Contact: Developer contact information and project description.

How to Run
1. Install Streamlit and other required libraries:

pip install streamlit plotly pandas Pillow

2. Run the app:

streamlit run airbnb.py


File Upload
Users can upload CSV, TXT, XLSX, or XLS files for analysis. If no file is uploaded, a default dataset is used.

Filters
- Neighborhood Group: Select one or more groups to filter the data.
- Neighborhood: Select specific neighborhoods within the chosen group(s).

Visualizations
- Room Type ViewData: Bar chart showing the sum of prices for each room type.
- Neighborhood Group ViewData: Pie chart showing the price distribution across neighborhood groups.
- Detailed Room Availability and Price View: Table showing detailed information for the first 500 listings.

Downloadable Data
Users can download filtered data as CSV files directly from the app.

Contact Section
Includes the developer's name, email, batch code, and GitHub link.

Deployment
The app is designed to be deployed and shared easily, providing insights into Airbnb's market dynamics.
