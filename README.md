# VE3_Task
Django-based web application that allows users to upload CSV files, performs data analysis using pandas and numpy, and displays the results and visualizations on the web interface.

# CSV Analysis Project

This is a Django-based web application that allows users to upload CSV files, perform data analysis using pandas and numpy, and display the results and visualizations on the web interface.

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd csv_analysis_project
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply the migrations:
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Start the development server:
    ```sh
    python manage.py runserver
    ```

6. Open a web browser and navigate to `http://127.0.0.1:8000/analysis/upload/` to upload a CSV file and view the analysis results.

## Project Explanation

This application allows users to upload CSV files and performs the following data analysis tasks:
- Displaying the first few rows of the data.
- Calculating summary statistics (mean, median, standard deviation) for numerical columns.
- Identifying and handling missing values.
- Generating histograms for numerical columns using matplotlib and seaborn.

## Sample CSV File

A sample CSV file for testing purposes is included in the repository.
File Name = CSV_Demo.csv
