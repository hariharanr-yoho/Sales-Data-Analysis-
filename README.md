Sales Data Analysis Project
About the Project

This project analyses sales data using Python and creates five visualisations to understand business performance.

Tools Used
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook
Project Structure
text
task3/
├── dataset.csv
├── Task_1_Five_Visualisations.ipynb
├── report.md
├── README.md
├── requirements.txt
├── Task_1_Five_Visualisations.html
└── reports/
    └── figures/
        ├── 01_bar_chart.png
        ├── 02_histogram.png
        ├── 03_scatter_plot.png
        ├── 04_line_chart.png
        └── 05_box_plot.png

Installation

Install Python and the Python and Jupyter extensions in VS Code.

Install the required libraries:

bash
py -m pip install -r requirements.txt

How to Run
Open this project folder in VS Code.
Open Task_1_Five_Visualisations.ipynb.
Select the Python kernel.
Run all notebook cells.
View the generated figures inside reports/figures/.
Export Notebook

Run:

bash
py -m jupyter nbconvert --to html Task_1_Five_Visualisations.ipynb

Key Findings
Electronics generated the highest revenue.
Clothing had the highest quantity sold.
Sales increased from January to May.
Conclusion

Data visualisation helps identify sales trends, compare categories, and support business recommendations.

Note: The dataset is simulated for educational purposes.