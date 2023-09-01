# Data-Analysis-Movie-datasets

This repository contains a Python script for performing data analysis on a movie dataset using popular libraries like Pandas, Seaborn, and Matplotlib. The analysis focuses on understanding various aspects of the movies, including actors, directors, ratings, budgets, and more.

## Prerequisites
Before running the script, ensure you have the following libraries installed:

1. Pandas
2. NumPy
3. Seaborn
4. Matplotlib
5. Google Colab (if running on Google Colab) or Jupyter Notebook

## Setup

1. Clone this repository using the command:
  ```
  git clone https://github.com/your-username/movie-analysis.git
  ```
 
2. Navigate to the repository directory:
   ```
   cd movie-analysis
   ```

3. Install the required libraries using:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter Notebook or Python script in your preferred environment.

2. If using Google Colab, upload the `movies.csv` dataset using the provided code snippet in the notebook.

3. The script performs the following steps:

- Reads and loads the movie dataset into a Pandas data frame.
- Displays basic information about the dataset using `df.info()`.
- Calculates the percentage of missing values in each column and prints the results.
- Removes rows with missing values using `df.dropna(inplace=True)`.
- Converts the data types of the 'budget' and 'votes' columns to integers.
- Splits the 'released' column into 'released_year' and 'released_month' columns.
- Computes statistics on top actors and directors based on movie count, gross income, and average earnings.
- Plots bar charts to visualize average earnings and ratings of top actors and directors.
- Displays a correlation heatmap of numeric columns in the dataset.

## Contributors

- Kumud Kohli - [GitHub Profile](https://github.com/kumudkohli)

Feel free to contribute to this project by opening issues or pull requests!




