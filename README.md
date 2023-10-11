# US-Traffic-Accidents-Data-Exploratory-Analysis

US Traffic Accidents Data Exploratory Analysis (2016 - 2020)

Motivation 

Traffic accidents in the United States have a significant economic and societal impact, costing citizens billions of dollars annually. This dataset contains extensive information on accidents occurring between 2016 and 2020 across 49 states. It was compiled using data from various sources, including government agencies, law enforcement, traffic cameras, and sensors. The dataset comprises approximately 7.7 million records and can be employed for various purposes, including real-time accident prediction, identifying accident hotspots, casualty analysis, and understanding the influence of environmental factors on accident occurrence.

Dataset Overview

The dataset contains the following attributes, categorized into four main groups:

Traffic Attributes (12):

ID: A unique identifier for each accident record.

Source: The source of the accident report, indicating the API that reported the accident.

TMC: A Traffic Message Channel code offering detailed information about the event.

Severity: A severity rating from 1 to 4, with 1 indicating minimal impact and 4 indicating significant traffic delays.

Start_Time: The local start time of the accident.

End_Time: The local end time of the accident.

Start_Lat: The latitude of the accident's starting point in GPS coordinates.

Start_Lng: The longitude of the accident's starting point in GPS coordinates.

End_Lat: The latitude of the accident's end point.

End_Lng: The longitude of the accident's end point.

Distance(mi): The length of the road affected by the accident.

Description: A natural language description of the accident.

Address Attributes (9):

Number: Street number in the address field.

Street: Street name in the address field.

Side: The relative side of the street (Right/Left).

City: The city in the address field.

County: The county in the address field.

State: The state in the address field.

Zipcode: The zipcode in the address field.

Country: The country in the address field.

Timezone: The timezone based on the accident's location.

Weather Attributes (11):

Airport_Code: Denotes the closest airport-based weather station to the accident location.

Weather_Timestamp: The timestamp of the weather observation record (local time).

Temperature(F): Temperature in Fahrenheit.

Wind_Chill(F): Wind chill in Fahrenheit.

Humidity(%): Humidity percentage.

Pressure(in): Air pressure in inches.

Visibility(mi): Visibility in miles.

Wind_Direction: Wind direction.

Wind_Speed(mph): Wind speed in miles per hour.

Precipitation(in): Precipitation amount in inches.

Weather_Condition: Weather condition (e.g., rain, snow, thunderstorm, fog).

POI Attributes (13):

Amenity: Presence of a Point-Of-Interest (POI) amenity nearby.

Bump: Presence of a speed bump or hump nearby.

Crossing: Presence of a crossing nearby.

Give_Way: Presence of a give-way sign nearby.

Junction: Presence of a junction nearby.

No_Exit: Presence of a no-exit sign nearby.

Railway: Presence of a railway nearby.

Roundabout: Presence of a roundabout nearby.

Station: Presence of a station (bus, train, etc.) nearby.

Stop: Presence of a stop sign nearby.

Traffic_Calming: Presence of traffic calming means nearby.

Traffic_Signal: Presence of a traffic signal nearby.

Turning_Loop: Presence of a turning loop nearby.

Period-of-Day (4):

Sunrise_Sunset: Period of the day based on sunrise/sunset.

Civil_Twilight: Period of the day based on civil twilight.

Nautical_Twilight: Period of the day based on nautical twilight.

Astronomical_Twilight: Period of the day based on astronomical twilight.

Citing the Dataset:

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. "A Countrywide Traffic Accident Dataset," 2019.

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights," in proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.
