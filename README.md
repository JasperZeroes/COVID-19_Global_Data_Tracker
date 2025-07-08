# COVID-19 Global Analysis and Visualization

This project presents a comprehensive data analysis of the COVID-19 pandemic using the **Our World in Data** dataset. It explores key metrics such as total cases, deaths, new daily cases, and vaccination progress across selected countries: **Kenya**, **United States**, and **India**.

The analysis includes:
- Data loading and cleaning
- Descriptive statistics
- Time-series visualizations
- Vaccination trend comparisons

---

##  Project Objectives

- Clean and preprocess a real-world COVID-19 dataset
- Perform exploratory data analysis (EDA) to identify trends and patterns
- Visualize the progression of COVID-19 cases, deaths, and vaccinations over time
- Compare key indicators between multiple countries
- Present insights using clear, well-labeled visualizations and narrative markdown

---

##  Tools & Libraries Used

- **Python** – programming language
- **Jupyter Notebook** – for code, narrative, and visual presentation
- **pandas** – data loading, manipulation, and analysis
- **matplotlib** – static plotting
- **seaborn** – statistical data visualization
- **plotly** *(optional)* – for interactive choropleth map
- **Our World in Data (OWID)** – COVID-19 data source

---

##  How to Run the Project

1. **Download the Dataset**  
   Go to [OWID COVID-19 Dataset](https://ourworldindata.org/covid-cases) and download the `owid-covid-data.csv`.

2. **Place the File**  
   Save `owid-covid-data.csv` in the same directory as the Jupyter Notebook.

3. **Run the Notebook**  
   Open `COVID-19_Global_Analysis_and_Visualization.ipynb` using Jupyter Notebook or JupyterLab and run all cells sequentially.

4. **Install Dependencies**  
   If needed, install required packages using:

   ```bash
   pip install pandas matplotlib seaborn plotly


## Insights & Reflections
 - India recorded the highest total cases among the selected countries.

- United States began vaccinations earlier and at a faster rate than Kenya or India.

- Kenya reported fewer total cases and deaths, but this may reflect limited testing/reporting capacity.

- The death rate showed a downward trend as vaccines and treatment protocols improved.

- Daily new cases show distinct waves that align with global COVID-19 variants (e.g., Delta, Omicron).

- Visualization proved essential in comparing the timeline and impact of the pandemic across regions.

## Future Improvements
- Incorporate more countries and continents

- Add stringency index or testing rate analysis

- Use dashboards for interactive data exploration (e.g., Streamlit or Dash)
