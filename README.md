## L2T08 - Data Visualisation - Python Libraries

### Data Visualization Task

This task involves generating specific graphs from the Cars93.csv dataset and analyzing based on the generated visualizations. Additionally, a multi-plot grid is created for the wine.csv dataset.

## Instructions

1. **Installation**
    - Make sure you have Python installed on your system. You can download it from the [Python website](https://www.python.org/downloads/).
    - Install Jupyter Notebook to run the provided notebooks. You can install it using pip:
```
        pip install notebook
```

2. **Running the Notebooks**
    - Clone this repository to your local machine using:
```
        git clone https://github.com/vswapna3202/L2T08
```
    - Navigate to the task's folder:
        ```
        cd L2T08 or cd <your_task_folder>
        ```
    - Start Jupyter Notebook:
        ```
        jupyter notebook
        ```
## Datasets
- Cars93.csv: Contains information about cars, including manufacturer, MPG, horsepower, etc.
- wine.csv: Contains information about various types of wines, including variety, points, etc.

**Plot Generation and Analysis - Cars93.csv Dataset**

1. Open the Jupyter notebook named `data_viz_task.ipynb`
2. Following plots have been generated for Cars93.csv dataset:
    - A box plot for the revs per mile for the Audi, Hyundai, Suzuki, and Toyota car manufacturers.
    - A histogram of MPG in the city, along with a histogram of MPG on the highway.
    - A line plot showing the relationship between the 'Wheelbase' and 'turning circle'.
    - A bar plot showing the mean horsepower for each car Type (Small, Midsize, etc.).
3. Based on the plots generated analysis has been done for the following:
    - Identify the manufacturer with the highest revs per mile
    - Fuel efficiency with respect to driving in city or on the highway.
    - Relationship between'Wheelbase' and 'turning circle' and what happens when wheelbase is larger
    - Analyse if large car has more horsepower if so analyse why.

**Plot Generation and Analysis - Wine.csv dataset**

1. Open the Jupyter notebook named `wine.ipynb`.

2. Following multi-plot grids have been created:
    - Filter the dataset to only contain “Cabernet Sauvignon”, “Pinot Noir”, and “Chardonnay” wines.
    - Use the variety column.
    - For each of these three wine varieties, show a histogram plot of the “points” column.



