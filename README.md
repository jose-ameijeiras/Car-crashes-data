# Car crashes data

## Description

This dataset, analysed in Ameijeiras-Alonso and Crujeiras (2021), consists of the time of the day when 85 car crashes happened at El Paso County (Texas, USA) in 2018. The data is available with a resolution of one minute. This dataset was obtained from the webpage of the National Highway Traffic Safety Administration of the United States (https://www-fars.nhtsa.dot.gov/). 

Data is available in CSV and RData format.

## Format

The data frame *car_crashes* contains the time of the day at which the car accident was produced. This is given in the format *hour* and *minute*. It is also provided in angles  (*angle_day*), measured in radians, in the clockwise sense, in the interval [0,2\pi), where the angle 0 coincides with the time 00:00.

The data frame *car_crashes_full_info* contains all the information available at the FARS website (https://www-fars.nhtsa.dot.gov/). This includes, among others the time of the year at which the accident was produced. This is given in the format of *MINUTE*, *HOUR*, *DAY*, and *MONTH*. It also provides the location, in *LATITUDE* and *LONGITUDE*, of the accident.  

## Reference:

Jose Ameijeiras-Alonso and Rosa M. Crujeiras (2021). Flexible circular modeling: a case study of car accidents. Under review. 
