# VE3_Task
Django-based web application that allows users to upload CSV files, performs data analysis using pandas and numpy, and displays the results and visualizations on the web interface.

# CSV Analysis Project

This is a Django-based web application that allows users to upload CSV files, perform data analysis using pandas and numpy, and display the results and visualizations on the web interface.

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd VE3_Task
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
    python manage.py makemigrations or py manage.py makemigrations
    python manage.py migrate or py manage.py migrate
    ```

5. Start the development server:
    ```sh
    python manage.py runserver or py manage.py runserver
    ```

6. Open a web browser and navigate to `http://127.0.0.1:8000/analysis/upload/` to upload a CSV file and view the analysis results.

## Project Explanation

This Django project allows users to upload CSV files, analyze them, and visualize the data. It provides the following main features:

- Upload CSV Files: Users can upload CSV files using a form.

- Data Analysis: The uploaded CSV file is analyzed to provide summary statistics such as mean, median, and standard deviation, as well as histograms for numeric columns.

- Data Visualization: Histograms are generated for each numeric column in the CSV file to visualize the data distribution.

- Automatic Deletion: Uploaded CSV files are scheduled for deletion after 10 minutes to manage disk space.

- Styles HTML tables for better visualization.

Requirements
- Python 3.x
- Django
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Sample CSV File

A sample CSV file for testing purposes is included in the repository.
Folder Name = Sample_CSV_Files

