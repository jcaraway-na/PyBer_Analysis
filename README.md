# PyBer_Analysis
## BACKGROUND

> V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

### OBJECTIVE

>This new assignment consists of two technical analysis deliverables and a written report to present your results. 
> You will submit the following:

- Deliverable 1: A ride-sharing summary DataFrame by city type
- Deliverable 2: A multiple-line chart of total fares for each city type
- Deliverable 3: A written report for the PyBer analysis (README.md)

---

### Deliverable 1: A ride-sharing summary DataFrame by city type

#### Requirements:
- :white_check_mark: The total number of rides for each city type is retrieved. 
- :white_check_mark: The total number of drivers for each city type is retrieved. 
- :white_check_mark: The sum of the fares for each city type is retrieved. 
- :white_check_mark: The average fare per ride for each city type is calculated. 
- :white_check_mark: The average fare per driver for each city type is calculated. 
- :white_check_mark: A PyBer summary DataFrame is created.
- :white_check_mark: The PyBer summary DataFrame is formatted as shown in the example. 

![This is an image](https://github.com/jcaraway-na/PyBer_Analysis/blob/main/Resources/pyber_summary_dataframe.png)

### Deliverable 2: A multiple-line chart of total fares for each city type

#### Requirements:
- :white_check_mark: (Img.1) A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time. 
- :white_check_mark: (Img.2) A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." 
- :white_check_mark: (Img.3) A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28. 
- :white_check_mark: (Img.4) A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week. 
- :white_check_mark: (Img.5) An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 


##### Img.1

![This is an image](https://github.com/jcaraway-na/PyBer_Analysis/blob/main/Resources/pyber_dataframe_groupby.png)

##### Img.2

![This is an image](https://github.com/jcaraway-na/PyBer_Analysis/blob/main/Resources/pyber_pivot_dataframe.png)

##### Img.3

![This is an image](https://github.com/jcaraway-na/PyBer_Analysis/blob/main/Resources/pyber_dataframe_loc.png)

##### Img.4

![This is an image](https://github.com/jcaraway-na/PyBer_Analysis/blob/main/Resources/pyber_dataframe_resample.png)

##### Img.5

![This is an image](https://github.com/jcaraway-na/PyBer_Analysis/blob/main/Resources/pyber_linechart.png)

### Deliverable 3:
