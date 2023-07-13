# Human Activity Monitoring - Time Series Analysis

This project focuses on extracting time series features for human activity monitoring using accelerometer data. It involves applying natural visibility graph (NVG), horizontal visibility graph (HVG), and computing permutation entropy and complexity. The project uses a dataset consisting of accelerometer data from 15 subjects for activities like walking, running, climbing up, and climbing down for head and chest positions.

## Dataset

The dataset for this project can be accessed through the following link: [Human Activity Dataset]([link-to-the-dataset](https://www.uni-mannheim.de/dws/research/projects/activity-recognition/dataset/))

## Task 1: Visibility Graph Analysis

In this task, the NVG and HVG methods are applied to the accelerometer data for each subject. The following computations are performed:

1. Calculation of average degree, network diameter, and average path length.
2. Selection of a sample size of 1024 data points for each of the 15 time series.
3. Tabulation of the results.
4. Generation of scatter plots: average degree vs network diameter, with points colored according to walking and running activities, for each accelerometer signal and each method (HVH and NVG).
5. Generation of scatter plots: average degree vs network diameter, with points colored according to climbing up and climbing down activities, for each accelerometer signal and each method (HVH and NVG).

## Task 2: Permutation Entropy and Complexity

In this task, permutation entropy and complexity are computed for the accelerometer data. The following parameters are varied:

1. Embedded Dimension: 3, 4, 5, 6.
2. Embedded Delay: 1, 2, 3.
3. Signal Length: 1024, 2048, 4096.

The following actions are performed:

1. Calculation of permutation entropy and complexity for the specified parameters.
2. Generation of scatter plots: permutation entropy vs complexity, with points colored according to walking and running activities, for signal length = 4096, embedded delay = 1, and embedded dimensions = 3, 4, 5, 6, for all three accelerometer directions.
3. Generation of scatter plots: permutation entropy vs complexity, with points colored according to climbing up and climbing down activities, for signal length = 4096, embedded delay = 1, and embedded dimensions = 3, 4, 5, 6, for all three accelerometer directions.
