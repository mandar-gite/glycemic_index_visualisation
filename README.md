# Visualisation of Glycemic Index 

This repository contains a Python script that analyzes the glycemic index and glycemic load of various foods. The script accesses data from a webpage using Pandas, cleans the data, and creates several plots using Matplotlib and Seaborn.
Requirements

    Python 3.6 or higher
    Pandas
    Seaborn
    Matplotlib

### Installation

    Clone this repository to your local machine.
    Install the required packages using pip:

`pip install pandas seaborn matplotlib `
 

### Usage

The glycemic_index_analysis.py script contains the following functionality:

    Accesses data from a webpage using Pandas.
    Cleans the data by resetting the index, deleting rows without glycemic index values, and removing the first and last rows of the dataframe.
    Creates several plots using Matplotlib and Seaborn:
        Bar plot of the top 10 foods with the highest glycemic index values.
        Bar plot of the bottom 10 foods with the lowest glycemic index values.
        Scatter plot of the glycemic index vs. glycemic load for all foods.
        Bar plot of the top and bottom two fruits by glycemic index.

### Contributing

Feel free to fork this repository and submit pull requests if you have any suggestions or improvements.
### License

This project is licensed under the MIT License.