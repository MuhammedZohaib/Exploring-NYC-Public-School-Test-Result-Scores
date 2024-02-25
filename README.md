# Project Name: School SAT Analysis

## Description:
This Python script analyzes SAT scores data for schools. It performs several calculations and filters to derive insights from the dataset. The main functionalities include:

1. Calculating the percentage of the math score for each school.
2. Filtering schools with a math percentage greater than or equal to 80% and sorting them by their average math score.
3. Calculating the total SAT score for each school.
4. Selecting the top 10 schools with the highest total SAT scores.
5. Grouping the data by borough and calculating standard deviation, mean, and count of total SAT scores for each borough.
6. Identifying the borough with the highest standard deviation in SAT scores.

## Instructions:
1. Ensure you have Python installed on your system.
2. Install required dependencies using `pip install pandas numpy`.
3. Download the dataset file named `schools.csv` and place it in the same directory as the script.
4. Execute the script by running `python <script_name>.py`.
5. View the output which includes information on schools with high math scores, top 10 schools with the highest total SAT scores, and the borough with the largest standard deviation in SAT scores.

## Usage:
```bash
python school_sat_analysis.py
```
Dependencies:
- `pandas`
- `numpy`

## Dataset:
The analysis is performed on the dataset schools.csv. This dataset contains information about schools including average math scores, average reading scores, average writing scores, and borough information.

## Output:
The script generates insights such as schools with high math scores, top 10 schools with the highest total SAT scores, and the borough with the largest standard deviation in SAT scores.
