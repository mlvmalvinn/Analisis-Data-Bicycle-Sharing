# Analisis-Data-Bicycle-Sharing
Hello, this project is part of Dicoding final test to pass "Belajar Analisis Dengan Python" course, this course's final project is to make a simple web app of a dashboard that displays information graph from selected csv file, and then use said file to do data analysis ranging from Data Wrangling, Exloratory Data Analysis and Data visualization (dashboard).

Dashboard is made using "streamlit" that allows me to create simple web apps like the one on the dashboard directory named "dashboard.py", it reads data only from "day.csv" file to function where it's supplied within the folder, you can access the streamlit dashboard Here: ([link](https://mlvmalvinnbicyclesharing.streamlit.app/))

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
├── requirements.txt
└── url.txt
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
-Clone This repository as zip then unzip it

-Go to the dashboard folder then right click the empty space or the folder itself to then open it with a code editor

-Run it and use the command:
streamlit run dashboard.py

(don't forget to install all the neccesary libraries)

## Screenshots of the dashboard
![Dashboard1](https://github.com/mlvmalvinn/dump/blob/main/Dashboard1.jpeg?raw=true)
![Dashboard1](https://github.com/mlvmalvinn/dump/blob/main/Dashboard2.jpeg?raw=true)

