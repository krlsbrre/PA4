# Data Wrangling and Data Visualization Project - Programming Assignment 4

## Description
This repository addresses Python-based data wrangling and data visualization tasks using Matplotlib, Pandas, and Seaborn. The experiment focuses on manipulating and analyzing the ECE Board Exam dataset and presenting the results using Python.

### Problem 1: Data Frame Creation
- **Task**: Create specific data frames based on given conditions from the ECE Board Exam dataset. You will generate different data frames by filtering data on certain features such as `Track`, `Hometown`, and `Gender`.
- Display the first and last five rows of the dataset.<br />
**Example output:** <br />
For Visayas hometown and `Math < 70`, create a dataframe with the columns `["Name", "Gender", "Track", "Math"]`.<br />
   [image](https://github.com/user-attachments/assets/3ba77655-085b-44a8-91f6-7050515b92b7)<br />
**Other required data frames include:**
- **Data Frame 1**(Filename: Instru):<br />
Columns: `["Name", "GEAS", "Electronics >70"]`<br />
Condition: Track = Instrumentation, Hometown = Luzon<br />
- **Data Frame 2**(Filename: Mindy):<br />
Columns: `["Name", "Track", "Electronics", "Average >=55"]`<br />
Condition: Hometown = Mindanao, Gender = Female

### Problem 2: Data Visualization
- **Task**: Create a visualization that shows how features such as `Track`, `Gender`, and `Hometown` contribute to the **average grade**.

## Getting Started

### Prerequisites
You need Python and `pandas`, `matplotlib`, and `seaborn` installed. To install `pandas`, `matplotlib`, and `seaborn`, run:

```bash
pip install pandas
pip install matplotlib
pip install seaborn
```

## Running the code

#### 1. Clone the repository:
```bash
git clone https://github.com/krlsbrre/PA4.git
```
#### 2. Navigate to the project directory and drag & upload the .ipynb file to Jupyter Notebook

## **Changelog**

See the [`CHANGELOG`](https://github.com/krlsbrre/PA4/releases) link for details.

## Author

- [@krlsbrre - Karlos Louis M. Sabarre - 2ECE-A - 2023184838](https://www.github.com/krlsbrre)
