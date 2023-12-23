This is a fork of https://github.com/mandar-gite/glycemic_index_visualisation

# Visualisation of Glycemic Index 

This repository contains a Python script that analyzes the glycemic index and glycemic load of various foods. The script accesses data from a webpage using Pandas, cleans the data, and creates several plots using Matplotlib and Seaborn.

Requirements:

- Python 3.6 or higher
- Pandas (Python library for data manipulation and analysis)
- Seaborn (Python data visualization library for creating attractive and informative statistical graphics)
- Matplotlib (Python library for creating static, animated, and interactive visualizations in various formats)
- Jypyter Notebook (Open-source web application that allows you to create and share documents containing live code, equations, visualizations, and narrative text)
    

### Installation

Clone this repository into a folder of your choice:

`git clone github.com/generallynonsensical/glycemic_index_visualisation`

then

`cd glycemic_index_visualisation`

-------

Create a Python Virtual Environment in the folder:

`python3 -m venv .venv`

then

`Source .venv/bin/activate`

-------

Install Pandas Seaborn Matplotlib and Jupyter using pip:

`pip install pandas seaborn matplotlib notebook`

 -------

### Usage

The glycemic_index_analysis.py script contains the following functionality:

Accesses data from a webpage using Pandas.
- Cleans the data by resetting the index, deleting rows without glycemic index values, and removing the first and last rows of the dataframe.
- Creates several plots using Matplotlib and Seaborn:
     - Bar plot of the top 10 foods with the highest glycemic index values.
     - Bar plot of the bottom 10 foods with the lowest glycemic index values.
     - Scatter plot of the glycemic index vs. glycemic load for all foods.
     - Bar plot of the top and bottom two fruits by glycemic index.

### Contributing

Feel free to fork this repository and submit pull requests if you have any suggestions or improvements.
### License

This project is licensed under the MIT License.
