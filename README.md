# Demographic Data Analyzer

A Python project that analyzes demographic data from the [Adult Census Income dataset](https://archive.ics.uci.edu/ml/datasets/adult). The project calculates statistics like average age, education levels, salary distribution, work hours, and occupation patterns using **Pandas**.

## Features

- Count of each race represented in the dataset.
- Average age of men.
- Percentage of people with a Bachelor's degree.
- Percentage of people with advanced education (`Bachelors`, `Masters`, `Doctorate`) earning more than 50K.
- Percentage of people without advanced education earning more than 50K.
- Minimum number of hours worked per week and the percentage of rich people among them.
- Country with the highest percentage of high earners.
- Most popular occupation for high earners in India.

demographic-data-analyzer/
│
├── main.py                      # Entrypoint to run the project
├── demographic_data_analyzer.py # Core analysis functions
├── test_module.py               # Unit tests
└── adult.data.csv               # Dataset
