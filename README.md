# 🌿 Analyzing the Impact of Climate Change on Public Health in India

This project investigates how climate variables—temperature, rainfall, and vegetation—affect public health in India. Using a dataset covering disease outbreaks across Indian states and districts from 2009 to 2023, the project performs data cleaning, storage, analysis, and visualization to uncover meaningful trends and correlations.

---

## 📌 Objectives

- Analyze the impact of climate indicators on public health outcomes.
- Identify high-risk diseases and vulnerable regions.
- Explore trends using Python, SQL, and data visualization.
- Derive actionable insights from epidemiological and environmental data.

---

## 🛠️ Tools & Technologies

- **Python**: Pandas, Matplotlib, Seaborn
- **SQL**: MySQL (via SQLAlchemy)
- **Jupyter Notebook**: For interactive analysis and visualization
- **Database**: MySQL (for structured querying and storage)

---

## 🗃️ Dataset Overview

- **Records**: 8,985 entries
- **Key Fields**:
  - `state_ut`, `district`, `disease`, `cases`, `deaths`
  - `day`, `month`, `year`
  - `temperature`, `precipitation`, `leaf area index (LAI)`
  - `latitude`, `longitude`

---

## 🔄 Data Cleaning (Using Pandas)

- Dropped irrelevant columns and standardized column names.
- Converted data types (e.g., `cases` and `deaths` to integers).
- Handled missing values in climate data using mean imputation.
- Ensured data consistency for further analysis and storage.

---

## 🗃️ MySQL Integration

- Created a MySQL database `climate_health`.
- Stored the cleaned dataset into a table `climate_health_data` using SQLAlchemy.
- Enabled structured querying and persistent storage.

---

## 📊 Exploratory Data Analysis (Pandas)

- Identified most common diseases and high-risk states.
- Analyzed trends in cases and deaths over time.
- Investigated correlation between temperature and outbreak intensity.
- Explored rainfall and vegetation's role in disease spread.

---

## 🧾 SQL Analysis (10 Key Queries)

- Total cases and deaths
- Year-wise trends in outbreaks
- Top 5 affected states and districts
- Diseases with highest fatality rates
- Climate-based disease distribution (e.g., by rainfall or temperature)

---

## 📈 Visualizations (Matplotlib & Seaborn)

- Bar plots for disease and state rankings
- Line charts for yearly trends
- Box plots for monthly temperature variations
- Heatmaps showing correlation between climate factors and disease metrics
- Scatter plots to visualize temperature vs. fatality

---

## 🔍 Key Insights

- **Diseases like Malaria and Diarrheal illness are highly climate-sensitive.**
- **Higher temperatures and increased rainfall correlate with spike in cases.**
- **Fatality rates rise in districts with extreme weather or poor infrastructure.**
- **South and Central India show higher vulnerability to climate-related outbreaks.**
