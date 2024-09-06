#  **Financial Forecasting Dashboard Using Tableau**

## **Project Overview**

This project involves the development of a professional-level financial forecasting dashboard using Tableau. The dashboard visualizes key financial metrics such as closing prices, daily returns, cumulative returns, and volatility analysis, providing insights into market trends and performance.

## **Dataset**

- **Source**: The dataset used in this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/camnugent/sandp500).
- **Description**: The dataset includes historical data of S&P 500 companies, comprising date-wise information about closing prices, volume, and other relevant metrics. It serves as a foundation for analyzing financial trends and making data-driven forecasts.

## **Tools and Technologies**

- **Tableau Desktop**: Used for creating interactive dashboards and visualizations.
- **Google Colab**: Employed for running Python scripts for data preprocessing and feature engineering.

## **Feature Engineering in Google Colab**

Feature engineering was performed using Python in Google Colab to prepare the data for analysis. Key steps included:

1. **Data Cleaning**:
   - Handled missing values and duplicates to ensure data quality.
   
2. **Feature Extraction**:
   - Extracted and calculated new features like daily returns, moving averages, and volatility.
   
3. **Calculations**:
   - Created additional features, including 7-day and 30-day moving averages for closing prices, daily returns, cumulative returns, and volatility analysis.

4. **Export**:
   - The cleaned and engineered dataset was exported in a format suitable for Tableau integration.

## **Tableau Desktop - Dashboard Creation**

The primary data visualization and analysis were performed using Tableau Desktop. The following key visualizations were created:

1. **Line Chart for Closing Prices**:
   - Displays the closing prices of selected S&P 500 stocks with 7-day and 30-day moving averages.
   - Highlights market trends and helps identify price movements over time.

2. **Line Chart for Daily Returns**:
   - Plots the daily returns of stocks, showcasing positive and negative movements, aiding in volatility analysis.
   - Visualizes financial performance and risk assessment.

3. **Area Chart for Cumulative Returns**:
   - Illustrates the growth of returns over time, offering insights into investment performance.
   - Emphasizes long-term gains or losses in the market.

4. **Line Chart for Volatility Analysis**:
   - Analyzes market volatility, depicting periods of high and low volatility to assist in risk management.
   - Uses historical data to highlight fluctuations in stock performance.

5. **Filters and Parameters**:
   - Added interactive filters and parameters to enable dynamic data exploration.
   - Users can select specific stocks, time ranges, and other criteria to customize the visualizations.

6. **Dashboard Layout**:
   - Integrated all visualizations into a cohesive dashboard.
   - Used borders, padding, and background colors to separate sheets, enhancing readability and aesthetics.

## **How to Use the Dashboard**

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/supriyamanda/Financial-Forecasting-Dashboard]

2. **Access Tableau Workbook**
- Open the Tableau workbook file (`.twbx`) in Tableau Desktop to explore the dashboard.
- Tableau public link: https://public.tableau.com/views/FinancialForcastingDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

3. **Data Source**
- The data source (`.csv` file) is already connected within the Tableau workbook. Ensure the file path matches when opening on a new machine.

4. **Explore the Dashboard**
- Interact with filters, hover over data points, and explore different time frames and stock analyses.

### **Conclusion**
This project provides a comprehensive tool for analyzing S&P 500 financial data, using feature engineering in Python and professional visualization techniques in Tableau. The dashboard enables data-driven decision-making, making it a valuable resource for financial analysts and investors.

