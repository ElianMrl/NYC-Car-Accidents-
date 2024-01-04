# Data Exploratory Analysis: Motor Vehicle Collisions - Crashes

Data Provided by: Police Department (NYPD)

Dataset Owner: NYC OpenData

Data Collection: Motor Vehicle Collisions

Database: [Motor Vehicle Collisions - Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)

The Motor Vehicle Collisions crash table contains details on the crash event. Each row represents a crash event. The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC. The police report (MV104-AN) is required to be filled out for collisions where someone is injured or killed, or where there is at least $1000 worth of damage. It should be noted that the data is preliminary and subject to change when the MV-104AN forms are amended based on revised crash details.For the most accurate, up to date statistics on traffic fatalities, please refer to the NYPD Motor Vehicle Collisions page (updated weekly) or Vision Zero View (updated monthly).

### Columns in this Dataset

| Column Name                   | Description                                                                                                                   | Type        |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ----------- |
| CRASH DATE                    | Occurrence date of collision                                                                                                  | Date & Time |
| CRASH TIME                    | Occurrence time of collision                                                                                                  | Plain Text  |
| BOROUGH                       | Borough where collision occurred                                                                                              | Plain Text  |
| ZIP CODE                      | Postal code of incident occurrence                                                                                            | Plain Text  |
| LATITUDE                      | Latitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326)                                       | Number      |
| LONGITUDE                     | Longitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326)                                      | Number      |
| LOCATION                      | Latitude , Longitude pair                                                                                                     | Location    |
| ON STREET NAME                | Street on which the collision occurred                                                                                        | Plain Text  |
| CROSS STREET NAME             | Nearest cross street to the collision                                                                                         | Plain Text  |
| OFF STREET NAME               | Street address if known                                                                                                       | Plain Text  |
| NUMBER OF PERSONS INJURED     | Number of persons injured                                                                                                     | Number      |
| NUMBER OF PERSONS KILLED      | Number of persons killed                                                                                                      | Number      |
| NUMBER OF PEDESTRIANS INJURED | Number of pedestrians injured                                                                                                 | Number      |
| NUMBER OF PEDESTRIANS KILLED  | Number of pedestrians killed                                                                                                  | Number      |
| NUMBER OF CYCLIST INJURED     | Number of cyclists injured                                                                                                    | Number      |
| NUMBER OF CYCLIST KILLED      | Number of cyclists killed                                                                                                     | Number      |
| NUMBER OF MOTORIST INJURED    | Number of vehicle occupants injured                                                                                           | Number      |
| NUMBER OF MOTORIST KILLED     | Number of vehicle occupants killed                                                                                            | Number      |
| CONTRIBUTING FACTOR VEHICLE 1 | Factors contributing to the collision for designated vehicle                                                                  | Plain Text  |
| CONTRIBUTING FACTOR VEHICLE 2 | Factors contributing to the collision for designated vehicle                                                                  | Plain Text  |
| CONTRIBUTING FACTOR VEHICLE 3 | Factors contributing to the collision for designated vehicle                                                                  | Plain Text  |
| CONTRIBUTING FACTOR VEHICLE 4 | Factors contributing to the collision for designated vehicle                                                                  | Plain Text  |
| CONTRIBUTING FACTOR VEHICLE 5 | Factors contributing to the collision for designated vehicle                                                                  | Plain Text  |
| COLLISION_ID                  | Unique record code generated by system. Primary Key for Crash table.                                                          | Number      |
| VEHICLE TYPE CODE 1           | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text  |
| VEHICLE TYPE CODE 2           | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text  |
| VEHICLE TYPE CODE 3           | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text  |
| VEHICLE TYPE CODE 4           | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text  |
| VEHICLE TYPE CODE 5           | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text  |
