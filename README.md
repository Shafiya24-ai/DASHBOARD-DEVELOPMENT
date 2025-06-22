# DASHBOARD-DEVELOPMENT

**COMPANY** : CODETECH IT SOLUTIONS

**NAME** : SHAIK SHAFIYA

**INTERN ID** : CT06DF1367

**DOMAIN** : DATA ANALYTICS

**DURATION** : 6 WEEKS

**MENTOR** : NEELA SANTHOSH KUMAR

## Interactive Sales Data Analytics Dashboard using Python, Dash, and Plotly

### Project Objective:

The primary objective of this project is to build a highly interactive and visually rich web-based dashboard for analyzing sales data across various dimensions. It allows users to explore sales trends, product performance, regional revenue distribution, and profitability insights dynamically. By selecting a region from a dropdown menu, the dashboard updates multiple charts and KPIs (Key Performance Indicators) in real time. This enables businesses and analysts to derive actionable insights without manually filtering or preprocessing data repeatedly.

The dashboard provides a holistic view of sales performance, identifies top-performing products, highlights monthly revenue trends, and visualizes category-wise revenue contribution. It also offers summarized business insights like total sales and average profit margins tailored to the selected region.

### Tools and Technologies Used:

- **Python:** The core programming language used for data handling, logic development, and integration.

- **Pandas:** Used for data loading, preprocessing, transformation, and aggregation operations such as calculating revenue and summarizing sales by region, product, and category.

- **Jupyter Notebook:** An interactive development environment where the dashboard was developed, allowing seamless execution of Python code, visualization rendering, and live testing of the dashboard within a notebook interface.

- **Dash (by Plotly):** A Python web application framework used to build the interactive dashboard, enabling real-time updates and interactive controls such as dropdown menus and dynamic plots.

- **Plotly Express:** Utilized to create advanced, interactive, and responsive visualizations like line charts (for sales trends), bar graphs (for product performance), and pie charts (for category revenue share).

- **HTML & CSS (via Dash components):** Used implicitly through Dash to define layout structures (html.Div, html.H1, etc.) and apply styling to headings, dropdowns, graphs, and summaries for better visual hierarchy and clarity.

- **CSV Dataset:** A structured .csv file containing sales data such as Date, Region, Product, Sales, Profit Margin, and Category, used as the backend data source for generating all analytics and visualizations in the dashboard.

### Description of the Dashboard and Code Functionality:

This dashboard is structured around interactive visual storytelling of business data. The code starts by loading the dataset using pandas.read_csv() with the proper path formatting (r"" to avoid unicode escape errors). Initial data preprocessing involves converting data types, calculating new metrics like revenue (by multiplying sales with profit margin), and extracting the month from the date field to enable time-based analysis.

**1. Dropdown for Region Selection**

At the core of the dashboard's interactivity is the dcc.Dropdown component. This dropdown dynamically populates with unique region names extracted from the dataset. When a user selects a region, the dashboard updates all visualizations to reflect data only for that region. This enables localized analysis without navigating away or filtering manually.

**2. Sales Over Time – Line Chart**

This section uses a line plot to display monthly sales trends. The data is grouped by 'Month' and summed to calculate total monthly sales for the selected region. It helps stakeholders observe seasonality, peak months, or sales dips.

**3. Top 10 Products – Bar Chart**

Using bar plots, the dashboard visualizes the top 10 best-selling products based on cumulative sales. This is critical for marketing and procurement teams to know which products drive revenue.

**4. Revenue by Category – Pie Chart**

To understand how various product categories contribute to overall revenue, a pie chart is created. The visual immediately shows revenue distribution and helps identify dominant or underperforming categories.

**5. Summary Statistics – Textual KPIs**

The html.Div is used to output summarized key insights:

- **Total Sales in the selected region**

- **Average Profit Margin**

These figures provide quick metrics for leadership and help interpret the visual data above more effectively.

### Use Case and Purpose:

The dashboard is especially useful for sales analysts, marketing teams, and business executives to:

- **Monitor performance by region**

- **Identify top-selling products and profitable categories**

- **Track sales growth or decline over months**

- **Gain quick executive summaries without diving into raw spreadsheets**

Instead of static reports, this dashboard provides real-time, interactive insights with minimal technical skill required to operate.

### Output:

![Image](https://github.com/user-attachments/assets/bb70eaf6-f4a2-4c96-8cad-c36ba9dccc37)
![Image](https://github.com/user-attachments/assets/8f62d08d-9878-456e-b92f-52262baeecab)
![Image](https://github.com/user-attachments/assets/773c98be-c689-4346-8aac-d05a9c8aa076)
![Image](https://github.com/user-attachments/assets/e7bd8b18-5198-4437-a1cb-5b62f771e78e)
   

