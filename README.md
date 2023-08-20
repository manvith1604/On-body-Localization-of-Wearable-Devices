# On-body-Localization-of-Wearable-Devices 

## Project - 1 

### a) Implement different clustering methods to synthetic and real-world data and validate using external and internal validation techniques

There are 8 datasets : <br/>
 [Data1.csv](Datasets/Data1.csv) ,  [Data2.csv](Datasets/Data2.csv) ,  [Data3.csv](Datasets/Data3.csv) ,  [Data4.csv](Datasets/Data4.csv) ,<br/>
 [Data5.csv](Datasets/Data5.csv) ,  [Data6.csv](Datasets/Data6.csv) ,  [Data7.csv](Datasets/Data7.csv) ,  [Data8.csv](Datasets/Data8.csv) 

1. Using K-means and hierarchical clustering methods to generate clusters
2. Evaluating the performance of the clustering algorithm using external validation
metrics
3. Plotting (2D or 3D) the data points for each dataset and coloring them according to the
original class
4. Plotting (2D or 3D) the data points for each dataset and coloring them according to the
class allocated by the clustering algorithm

### b) The world indicators dataset compares different countries based on selected attributes. <br/>
[world_indicators.csv](Datasets/World_Indicators.csv)

1. Using K-means and hierarchical clustering methods to group similar countries
together
2. Using Internal validation metrics to report the cluster quality
3. Reporting the best clustering solution. Giving a detailed list of all the groups and the
countries included within the groups
4. Generating three different scatter plots of your choice and color the data points
according to the group. Example: “Life expectancy vs GDP”, “Infant Mortality vs
GDP”, etc.
 
## Project - 2

The following [link](https://www.uni-mannheim.de/dws/research/projects/activity-recognition/dataset/dataset-realworld/) provides human activity data for 15 subjects. Click on each subject to
access the time series data. For this project consider accelerometer data for all the 15
subjects for walking, running, climbing up and climbing down

### Task 1
1. Applying natural visibility graph (NVG) and horizontal visibility graph (HVG) to the
aforementioned data
2. Computing average degree, network diameter, and average path length
3. For the above computations selecting sample size of 1024 data points ( from 1000
to 2024) for each of the 15 time series
4. Tabulating all the results
5. Generating scatter plots: average degree vs network diameter and coloring the points
according to walking and running (do this for each accelerometer signal and
each method (HVH and NVG))
6. Generating scatter plots: average degree vs network diameter and coloring the points
according to climbing up and climbing down (do this for each accelerometer
signal and each method (HVH and NVG))

### Task 2
1. Compute permutation entropy and complexity for the aforementioned data.
Consider the accelerometer data in all three directions
2. Varying the following parameters<br/>
Embedded Dimension 3, 4, 5, 6<br/>
Embedded Delay 1, 2, 3<br/>
Signal length 1024, 2048, 4096
3. Generating scatter plots: permutation entropy vs complexity and coloring the points
according to walking and running (for signal length =4096, embedded delay = 1,
and embedded dimension = 3, 4, 5, 6, and all three accelerometer directions)
4. Generating scatter plots: permutation entropy vs complexity and coloring the points
according to climbing up and climbing down (for signal length =4096, embedded
delay = 1, and embedded dimension = 3, 4, 5, 6, all three accelerometer
directions)
