# Residential-EV-Charging
A project on residential Electric Vehicle charging

Use Case
Charging time/Session Duration Prediction
Energy consumption/EnergyLoad Prediction

Data have been collected from a large housing cooperative in Norway, with 1,113 apartments and 2,321 residents. A new infrastructure for EV charging was installed from December 2018. From December 2018 to January 2020, charging sessions were registered by 97 user IDs; 82 of these IDs appeared to be still active at the end of the period. In the data provided with this article, Central European Time (CET) zone is used

Dataset 1: EV charging reports
The CSV file “Dataset 1” describes 6,878 individual charging sessions, registered by 97 user
IDs from December 2018 to January 2020. The charging reports include plug-in time, plug-out
time and charged energy per charging session. Each charging session is connected to a user
ID, charger ID and address.

Dataset 2: Hourly EV charging loads and idle capacity, for all sessions and users individually
The CSV file “Dataset 2” describes EV charging loads and non-charging idle capacity for each
user and all EV charging sessions individually. Charging power 3.6 kW or 7.2 kW is assumed, with immediate charging after plug-in. The non-charging idle time reflects the flexibility potential for the charging session. Synthetic idle capacity is the energy load that could potentially have been charged during the idle times.

Dataset 3: Hourly EV charging loads and idle capacity, aggregated for private or shared CPs
The CSV files “Dataset 3a” and “Dataset 3b” describe EV charging loads and idle capacity,
aggregated for users with private (3a) or shared (3b) CPs. Charging power 3.6 kW or 7.2 kW
is assumed, with immediate charging after plug-in.

Dataset 5: Hourly smart meter data from garage Bl2
The CSV file describes hourly smart meter data from garage Bl2, with aggregated electricity use each hour. The EVs were parked in 24 locations, whereof 22 locations have an AMS-meter measuring aggregated EV-charging at that location, with hourly resolution AMS-measurements from a main garage, where 33% of the charging sessions took place (2,243 charging sessions).

Dataset 6: Local traffic density
Local hourly traffic density in 5 nearby traffic locations. The data includes an hourly count of vehicles shorter than 5.6 meter, from December 2018 to January 2020.

Dataset 7: Weather Data
Local Weather Data of Trondheim, Norway.The data includes weather features like temperature, rainfall etc from December 2018 to January 2020.
