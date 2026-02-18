# Data Science Salaries Analysis Dashboard

This project is the result of studies during the Alura Data Immersion, focusing on creating an interactive dashboard to analyze salary data in the data science field.

## About the Project

The main application, `app.py`, is an interactive dashboard built with Streamlit. It allows users to explore salary data with various filters and visualizations. The primary libraries used are:

- **Streamlit:** For creating the web application and interactive components.
- **Pandas:** For data manipulation and analysis.
- **Plotly:** For creating interactive charts and graphs.

### Data Source

The data used in this dashboard is originally from the `df_limpo.csv` file, which contains cleaned and preprocessed salary information. In the application, the data is loaded directly from a remote URL for convenience.

## Features

- **Interactive Filters:** Users can filter the data by:
    - Year
    - Seniority level
    - Contract type
    - Company size
- **Key Metrics:** The dashboard displays key performance indicators (KPIs) such as:
    - Average salary
    - Maximum salary
    - Total number of records
    - Most frequent job title
- **Visualizations:** The dashboard includes several interactive plots:
    - Top 10 job titles by average salary.
    - Distribution of annual salaries.
    - Proportion of remote vs. on-site work.
    - Average Data Scientist salary by country.
- **Detailed Data Table:** A table with the filtered data is displayed at the end of the dashboard.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    The `requirements.txt` file lists all the necessary libraries.
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application:**
    ```bash
    streamlit run app.py
    ```
