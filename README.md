# Ride_Share_Analysis

## Objective
I analyzed data for ride sharing services to determine how often different types of cities use this service.  My goal is to figure out how ride sharing can be increased in underserved areas. 

This project marks the first time I used Matplotlib.  Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.  Matplotlib can be used to do the following:

- Create publication quality plots.
- Make interactive figures that can zoom, pan, update.
- Customize visual style and layout.
- Export to many file formats.
- Embed in JupyterLab and Graphical User Interfaces.
- Use a rich array of third-party packages built on Matplotlib.

I also used Numpy and SciPy to get the measures of central tendency and summary statistics for each city type.

### Tasks:
    - Analyzed all ride share data from Jan to early May 2019. (Numpy, SciPy)
    - Created a visualization of my findings with bubble charts, pie charts, box-and-whisker plots, and a  multiple-line graph. (Matplotlib)
    - Created a summary DataFrame of the ride sharing data by city type. (Pandas)
    

## Resources

### Libraries
- Matplotlib 3.5.0 (graphing)
- Numpy 1.20.3 (numerical mathematics)
- Pandas 1.3.5 (data analysis)
- SciPy 1.7.3 (mathematical computing)
- Python 3.7.11

### Software 
- Jupyter Notebook 6.4.5

### Data/Sources
- city_data.csv
- ride_data.csv
- PyBer_ride_data.csv
- https://matplotlib.org/ 

## Results
    
### Ride Sharing Data By City Type

![PyBer_Summary](https://user-images.githubusercontent.com/33010018/150711580-5ac53f8f-8131-4934-8dd6-152bdea5ebff.png)

### Monthly Total Fares By City Type

![image](https://user-images.githubusercontent.com/33010018/169484450-40b02f02-58b9-499a-9f91-6048ca13a818.png)

### Average Fares Vs. Driver Count By City Type
Note: Circle size correlates with the driver count per city.

![image](https://user-images.githubusercontent.com/33010018/169485680-f6155e87-62f7-425c-a88d-283164ae09c6.png)



 - Urban cities have the highest total number of drivers, total number of riders, and total fare price. 
 - Rural cities have a higher average fare price.
 - Rural cities have the lowest driver count, rider count, and total fare price.




### Total Weekly Fares For Each City Type
 
![Fares_by_wk](https://user-images.githubusercontent.com/33010018/150711594-c7645b74-8444-40cf-a727-cbb90e197f57.png)

- Urban cities have the highest total fares per week and the lowest average fare per ride ($24.53).
- Rural cities have the lowest total fares per week and the higest average fare per ride ($34.62)

## Analysis On How We Can Increase Ride Sharing 
- We could increase the total number of rides in rural cities by decreasing the fare price.
- We could increase the total number of rides in rural cities by increasing the total number of drivers in rural areas.
- Since urban cities are usually more densely populated, we could decrease the fare price and maybe more people will use ride sharing services.
