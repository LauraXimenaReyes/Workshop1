# Python Data Engineer Workshop

## Introduction

Welcome to the Python Data Engineer Workshop. This project demonstrates the practical application of a data engineering challenge, simulating a job interview experience. The main goal is to showcase the ability to handle data using Python, perform ETL processes, and generate insightful visualizations.

## Project Overview

The project involves working with a dataset of candidates who participated in selection processes for a job. The data is randomly generated and contains information such as the candidate's name, email, country, application date, years of experience, seniority, technology stack, and scores from a code challenge and technical interview.

The primary objective is to migrate this data into a relational database and create visualizations to display specific metrics. The visualizations include:

- Distribution of hires by technology (pie chart)
- Hires categorized by year (horizontal bar chart)
- Hires segmented by seniority (bar chart)
- Hires across years for select countries (USA, Brazil, Colombia, Ecuador) displayed through a multiline chart

A candidate is considered hired if both the code challenge score and the technical interview score are greater than or equal to 7.

## Technologies Used

- Python
- pandas
- psycopg2
- JSON
- Jupyter Notebook
- PostgreSQL

## Getting Started

To get started with this project:

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Set up a PostgreSQL database and configure the connection details in a JSON file named `finaldatabase.json`.
4. Run the provided Python script to perform the ETL process and load the data into the database.
5. Use Jupyter Notebook to execute the script and generate the visualizations.

## Considerations

- Ensure that the PostgreSQL database is correctly set up and accessible.
- The CSV file containing the candidate data should be properly formatted and named `candidates.csv`.
- The JSON file `finaldatabase.json` should contain the database connection details, including the host, user, password, and database name.

## Usage

The Python script performs the following tasks:

1. Reads the candidate data from the CSV file.
2. Establishes a connection to the PostgreSQL database.
3. Creates a table named `Candidates` in the database.
4. Inserts the candidate data into the table.
5. Fetches the updated data from the database.
6. Generates the required visualizations based on the updated data.

## Conclusion

This project provides a hands-on experience in data engineering, covering aspects such as data manipulation, database interaction, and data visualization. It serves as a valuable addition to a portfolio, showcasing skills relevant to a Python Data Engineer role.

For any questions or assistance, feel free to reach out to lauraximena21.03@gmail.com
