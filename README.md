# **Formula 1 Race Analysis Project**

This project analyzes Formula 1 race data, focusing on top drivers, team performance, and trends over the years. The dataset is processed using **Python**, with visualizations generated using **Plotly** for interactive insights. The cleaned data is then exported for further analysis in **Power BI**.

---

## **Project Overview**

- **Objective**: To analyze Formula 1 race results and provide insights on the top drivers, teams, and trends in F1 racing.
- **Dataset**: [Ergast API Dataset](https://ergast.com/mrd/).
- **Techniques Used**:
  - Data preprocessing and merging multiple datasets.
  - Analyzing top drivers and teams by podium finishes and wins.
  - Tracking team performance over the years.
  - Visualizing insights using Plotly and Power BI.

---

## **Key Features**

1. **Python Implementation**:
   - Extract and clean data from multiple CSV files (races, results, drivers, constructors).
   - Merge datasets for comprehensive analysis.
   - Identify top drivers by podium finishes and top teams by wins.
   - Analyze team performance over the years.
   - Export cleaned and merged data for Power BI integration.

2. **Plotly Visualizations**:
   - **Top Drivers by Podium Finishes**: Bar chart of the top 10 drivers.
   - **Top Teams by Wins**: Bar chart of the top 10 teams.
   - **Team Wins Over the Years**: Line plot showing team performance over time.

3. **Power BI Visualization**:
   - **Interactive Dashboard**: Import the processed data into Power BI for an interactive exploration of the F1 data.

4. **Insights**:
   - Identify the most successful drivers and teams.
   - Track the performance of teams over time.
   - Understand trends and patterns in F1 races.

---

## **Project Structure**

- **Python Script**:
  - f1_analysis.py: Full Python code for data extraction, preprocessing, merging, and visualization.

- **Dataset**:
  - races.csv: Race details (name, year, etc.).
  - results.csv: Results of each race (positions, points).
  - drivers.csv: Driver details.
  - constructors.csv: Team (constructor) details.

- **Power BI File**:
  - F1_Analysis_Dashboard.pbix: Interactive Power BI dashboard for exploring the insights.

- **Clustered Results**:
  - processed_race_data.csv: CSV file containing cleaned and merged race data for use in Power BI.

---

## **Tools & Libraries**

- **Python**:
  - Libraries: pandas, numpy, matplotlib, plotly
- **Power BI**:
  - For interactive dashboard creation and visualization.

---

## **How to Run the Project**

1. Clone this repository:
   
   ```bash
   git clone https://github.com/your-username/f1-race-analysis.git
