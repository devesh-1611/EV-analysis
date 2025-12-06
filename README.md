# EV-analysis

The EV Analysis project focuses on understanding the electric vehicle (EV) market using real-world data.
This includes exploratory data analysis (EDA), geospatial mapping, trend analysis, manufacturer market share, and visual analytics.

The project was executed in a Jupyter Notebook (EV_analysis.ipynb) and uses Python-based data science tools to transform raw vehicle datasets into meaningful business insights.

EV_Analysis/
│── EV_analysis.ipynb         # Main analysis notebook
│── data/                     # Raw and cleaned datasets (optional folder)
│── README.md                 # Project documentation (this file)

Technologies Used

Python 3

Pandas

NumPy

Matplotlib / Seaborn

Plotly (optional interactive charts)

Folium (for geo-mapping)

Jupyter Notebook

Installation & Setup
1. Clone the repository
git clone <your-repo-link>
cd EV_Analysis

2. Install required libraries

If you have a requirements.txt:

pip install -r requirements.txt


If not, install manually:

pip install pandas numpy matplotlib seaborn plotly folium jupyter

3. Launch the notebook
jupyter notebook EV_analysis.ipynb


Key Analysis Performed
1. Data Cleaning

Handling missing values

Fixing inconsistent column names

Dropping duplicates

Converting datatypes (e.g., to datetime)

Exploratory Data Analysis (EDA)

Summary statistics

Distribution of:

Vehicle types

Fuel types

Manufacturers

EV registrations by year

Outlier detection


Year-Wise Trend Analysis

Line charts for yearly EV registrations

Growth rate calculations

Market Share of EV Manufacturers

Computed manufacturer-wise sales

Percentage contribution

Designed pie charts & bar charts for clear visualization


Visualizations Included

Line charts (Year trends)

Bar charts (Top EV manufacturers)

Heatmaps

Folium maps

Pie charts (Market share)

Insights Summary

Some insights typically generated in such analysis:

EV registrations show a consistent upward trend year over year.

Certain manufacturers dominate market share.

Urban regions show higher EV density due to better charging infrastructure.

Popular EV models contribute significantly to total market sales


Author

Devesh Sharma
M.Sc. Data Science & Analytics
