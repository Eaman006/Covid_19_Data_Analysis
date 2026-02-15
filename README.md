# COVID-19 Data Analysis & Visualization

A data analysis project that explores the global spread of COVID-19 using Python. This notebook processes global dataset records to visualize the impact of the pandemic across different countries and continents using interactive charts.

## 🚀 Project Overview

The goal of this project is to clean, analyze, and visualize COVID-19 data to identify trends in confirmed cases, deaths, recoveries, and testing rates.

**Key Features:**
* **Data Cleaning:** Handling missing values and preparing datasets for analysis.
* **Interactive Tables:** Browsable data summaries using Plotly.
* **Bar Charts:** Comparative analysis of Total Cases, Deaths, and Tests across top countries.
* **Bubble Charts:** Visualizing the spread and magnitude of the virus across continents and countries.
* **Scatter Plots:** Logarithmic scale analysis of cases vs. other metrics.

## 🛠️ Technologies Used

* **Python**
* **Pandas** (Data manipulation)
* **Plotly Express & Graph Objects** (Interactive visualizations)
* **Matplotlib** (Static plotting)
* **Jupyter Notebook**

## 📂 Datasets

The project uses the following datasets:
1.  `covid.csv`: Contains country-wise detailed statistics (Population, Total Cases, Deaths, Recovered, Tests, etc.).
2.  `covid_grouped.csv`: Time-series data grouped by region.

## 📉 Viewing the Notebook (Important)

**GitHub does not render interactive Plotly graphs.**
If you view `project.ipynb` directly on GitHub, the graphs will appear as blank spaces.

To view the interactive visualizations, please use **nbviewer**:
[**Click here to view the notebook with interactive graphs**](https://nbviewer.org/) *(Paste the link to your GitHub notebook here)*

Alternatively, you can run the notebook locally.

## ⚙️ Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Install the required libraries:**
    ```bash
    pip install pandas plotly matplotlib
    ```
3.  **Run the Notebook:**
    ```bash
    jupyter notebook project.ipynb
    ```

## 📊 Analysis Highlights

* **Global Impact:** USA, Brazil, and India were identified as the most affected nations based on total cases.
* **Testing vs. Cases:** Analysis of how testing rates correlate with reported case numbers.
* **Regional Trends:** Grouped data analysis showing the spread across WHO regions (Americas, Europe, South-East Asia, etc.).

---
*Created by MD Eaman Adeep*
