# Pandas Tutorial
This tutorial will guide you throught the main feature of *pandas* and test your knowledge on the way.

The tutorial culminates in a Capstone Project where you can test you data processing and analysis skills.

The *solutions* folder contains solutions to all exercises and the answer to the given Capstone Project.

# Usage
If you just want to play around with some of the notebooks, I suggest using [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gabrielecalvo/pandas_tutorial/master). Note: it might take a few minutes to startup but will then give you access to an ephemeral Jupyter environment that has access to all notebooks in this reporitory. As it is ephemeral, once you close the browser all your work will disappear unless you download a copy of it.

In alternative you can use [Colab](https://colab.research.google.com), selecting the GitHub tab and enter `gabrielecalvo/pandas_tutorial` in the search input. You will have to select and open each notebook separately, but it will be easier to copy them to your google drive to edit and store.

## Syllabus
1. Introduction
    - Data Used
    - Useful links
    - Library version
1. Reading/Creating data
    - read_..
    - using additional options
    - pd.DataFrame constructors
1. Exploring data
    - first/last/random rows
    - shape, describe, dtypes
    - columns, index
    - value_counts(normalize)
    - unique
1. Subsetting data
    - Bracket/Dot notation (& slicing)
    - loc, iloc
    - filter by column value
    - multiple filters
1. Data Aggregation & Reshaping
    - groupby (+ agg)
    - pivot_table
    - sorting by index, values, multiple-values
    - stack, unstack
1. Data Plotting
    - plot types
        - line plot
        - scatter plot
        - bar chart
        - frequency histogram
    - main features:
        - adding grid, resizing the figure, changing color, etc..
        - setting axis limits
        - overlaying plots
        - multiple plots in one figure
        - saving to file
1. Data Manipulation
    - renaming columns
    - adding column, index
    - remove column, index
    - parsing: astype, pd.to_datetime
    - concat DataFrames
    - remove duplicate
    - apply, map, applymap
    - transposing
1. Handling Missing Data
    - isna, notna (+ sum, mean)
    - dropna (any, all)
    - fillna
1. Extra Tips
    - .str .dt methods
    - pd.set/reset_option (search from pd.describe_option())
1. Capstone Project
