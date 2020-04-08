# Performance-Of-Tools

1) Studied the relative performance of a set of tools: HDF5, VAEX, DASK, PANDAS.
2) Dataset used: Green Taxi Company, NYC data.
3) Converted a collection of CSV files into one single HDF5 file.
4) Measured the time it takes by each set of tool in performing the following task and compared them:
    4.1) Plot the number of unique trips with certain number of passengers in the entire green taxi data. (Green taxis can not operate in parts of NYC.)
    4.2) Filter out the trips longer than 100 miles and trips that claim more than 10 people.
    4.3) On the filtered data produce a heat map by pick up location color coded by average fare amount
    4.4) Compute the arc distance for the filtered data and plot the distribution number of trips of trip distance and arc distance

