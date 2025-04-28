📊 Pharmaceutical Drug Spending Analysis
Project Overview
This project analyzes pharmaceutical spending across countries and years based on a provided dataset.
It explores key economic indicators such as:

Spending per capita (USD)

Spending as % of Health Expenditure

Spending as % of GDP

Total National Pharmaceutical Spending

The goal is to uncover global trends, country comparisons, and economic relationships related to pharmaceutical expenses.

📂 Dataset Description

Column Name	Description
LOCATION	Country code (ISO format)
TIME	Year (e.g., 1971, 2020)
PC_HEALTHXP	Pharmaceutical spending as a percentage of total Health Expenditure
PC_GDP	Pharmaceutical spending as a percentage of GDP
USD_CAP	Pharmaceutical spending per capita (USD, PPP adjusted)
TOTAL_SPEND	Total Pharmaceutical Spending in millions of USD
📅 Covers multiple countries across decades.

🌎 Allows international comparison of healthcare economies.

📈 Useful for trend analysis, economic health study, and policy research.

🚀 Project Workflow
1. Data Loading
CSV data loaded using pandas.

Initial inspection: data types, missing values.

2. Data Cleaning
Verified no missing data.

Confirmed correct numeric and categorical columns.

3. Exploratory Data Analysis (EDA)
Global pharmaceutical spending trends over time.

Top 5 countries by per capita spending.

Correlation heatmap between Health Expenditure %, GDP %, and per capita spending.

4. Insights on Latest Year
Identified Top 10 and Bottom 10 countries by per capita pharmaceutical spending.

Bar charts to visualize disparities.

5. Clustering (Optional)
Used KMeans Clustering to group countries based on similar spending behaviors.

Visualized clusters based on GDP % and USD per capita.

📊 Key Findings
Pharmaceutical spending has steadily increased worldwide.

Developed countries (e.g., USA, Switzerland) are the top spenders per capita.

Strong positive correlation between pharmaceutical spending and both Health Expenditure % and GDP %.

Emerging economies spend much less per capita but are slowly increasing spending trends.

Clustering reveals clear separation between high-spending and low-spending countries.

📦 Technologies Used
Python 3.9

pandas

matplotlib

seaborn

scikit-learn (for clustering)

📁 How to Run This Project
Install dependencies:

bash
Copy
Edit
pip3 install pandas matplotlib seaborn scikit-learn
Clone the repository or download the code.

Ensure your CSV file is correctly referenced in the notebook.

Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Open the notebook file and run all cells.

🎯 Future Improvements
Add forecasting models (e.g., ARIMA) for future pharmaceutical spending.

Build an interactive dashboard using Plotly or Dash.

Deeper country-wise policy impact analysis.

🤝 Contributing
Feel free to fork this repository, open issues, or submit pull requests for improvements!

📜 License
This project is open-source and free to use under the MIT License.

🌟 Thank you for checking out this project!
