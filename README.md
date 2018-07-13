# Taxi-Pickup-Prediction-New-York
Main objective of tis project is to find number of pickups, given location cordinates(latitude and longitude) and time, in the query reigion and surrounding regions. For achiving this divided New York city into regions based on clustering  of pickupts wit latitude and logitude. after tat for each cluster/region divided data into time bins of 10 min because in data explaration got average speed in newyork is 12.45 miles/hour so 2 miles/10 min. Driver can travel with in 2 miles for incresing his pickup chance so divided into 10 min bins and predicting no of pickups in next 10 min in that region/cluster using some time series techniques and regression methods. 

##### Problem statement :
to find number of pickups, given location cordinates(latitude and longitude) and time, in the query reigion and surrounding regions

##### Real-world/Business objectives and constraints:
1. some low-latency requirement.
2. Interpretability is not much important.

##### Data :
got data from http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml
