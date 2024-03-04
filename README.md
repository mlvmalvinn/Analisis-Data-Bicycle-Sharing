# Analisis-Data-Bicycle-Sharing
Hello, this project is part of Dicoding final test to pass "Belajar Analisis Dengan Python" course, this course's final project is to make a simple web app of a dashboard that displays information graph from selected csv file, and then use said file to do data analysis ranging from Data Wrangling, Exloratory Data Analysis and Data visualization (dashboard).

Dashboard is made using "streamlit" that allows me to create simple web apps like the one on the dashboard directory named "dashboard.py", it reads data only from "day.csv" file to function where it's supplied within the folder, you can access the streamlit dashboard [here] (link)

## File Structures
```
.
├── dashboard
│   ├── dashboard.py
│   └── day.csv
├── data
│   ├── Readme.txt
│   ├── day.csv
|   └── hour.csv
├── README.md
├── notebook.ipynb
└── requirements.txt
```

## Project cycle
1. Data Wrangling: 
 - Gathering data
 - Assessing data
 - Cleaning data
2. Exploratory Data Analysis:
 - Defined business questions for data exploration
 - Create Data exploration
3. Data Visualization:
 - Create Data Visualization that answer business questions
4. Dashboard:
 - Set up the DataFrame
 - Make filter components on the dashboard
 - Complete the dashboard with sufficient data visualizations

## Setup environment
conda create --name main-ds python=3.9
conda activate main-ds

pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel

## Run steamlit app
streamlit run dashboard.py

