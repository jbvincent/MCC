# MCC

Script and functions to create multivariate control charts for visualization of longitudinal variation in ecological communities. Initially aimed at YTC case but ideally generalized to any input. 

Functionality includes producing extracting values and producing visualizations for any reference time point, allowing for use to explore change from initial census, previous year, or any other timepoint of interest. Bootstrapping routines are built to be carried out on either full data or stratified by classes of disturbance. 

Plotting is implemented in ggplot2 and can be stratified by disturbance class or produced for the full data set. 
