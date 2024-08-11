# Prodigy_DS_05
Welcome!!! This repository documents are for Task 5 which is last task of my internship journey, focusing on complete analysis through EDA and uncovering insightful patterns.
# Complete Analysis on US Accidents
**Task**---
Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.

# About
The economic and societal impact of traffic accidents cost U.S. citizens hundreds of billions of dollars every year. And a large part of losses is caused by a small number of serious accidents. Reducing traffic accidents, especially serious accidents, is nevertheless always an important challenge. The proactive approach, one of the two main approaches for dealing with traffic safety problems, focuses on preventing potential unsafe road conditions from occurring in the first place. For the effective implementation of this approach, accident prediction and severity prediciton are critical. If we can identify the patterns of how these serious accidents happen and the key factors, we might be able to implement well-informed actions and better allocate financial and human resources.

# Overview the dataset
--- Details about features in the dataset:

**Traffic Attributes (12):**

ID: This is a unique identifier of the accident record.

Source: Indicates source of the accident report (i.e. the API which reported the accident.).

TMC: A traffic accident may have a Traffic Message Channel (TMC) code which provides more detailed description of the event.

Severity: Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay).

Start_Time: Shows start time of the accident in local time zone.

End_Time: Shows end time of the accident in local time zone.

Start_Lat: Shows latitude in GPS coordinate of the start point.

Start_Lng: Shows longitude in GPS coordinate of the start point.

End_Lat: Shows latitude in GPS coordinate of the end point.

End_Lng: Shows longitude in GPS coordinate of the end point.

Distance(mi): The length of the road extent affected by the accident.

Description: Shows natural language description of the accident.

**Address Attributes (9):**

Number: Shows the street number in address field.

Street: Shows the street name in address field.

Side: Shows the relative side of the street (Right/Left) in address field.

City: Shows the city in address field.

County: Shows the county in address field.

State: Shows the state in address field.

Zipcode: Shows the zipcode in address field.

Country: Shows the country in address field.

Timezone: Shows timezone based on the location of the accident (eastern, central, etc.).

**Weather Attributes (11):**

Airport_Code: Denotes an airport-based weather station which is the closest one to location of the accident.

Weather_Timestamp: Shows the time-stamp of weather observation record (in local time).

Temperature(F): Shows the temperature (in Fahrenheit).

Wind_Chill(F): Shows the wind chill (in Fahrenheit).

Humidity(%): Shows the humidity (in percentage).

Pressure(in): Shows the air pressure (in inches).

Visibility(mi): Shows visibility (in miles).

Wind_Direction: Shows wind direction.

Wind_Speed(mph): Shows wind speed (in miles per hour).

Precipitation(in): Shows precipitation amount in inches, if there is any.

Weather_Condition: Shows the weather condition (rain, snow, thunderstorm, fog, etc.).

**POI Attributes (13):**

Amenity: A Point-Of-Interest (POI) annotation which indicates presence of amenity in a nearby location.

Bump: A POI annotation which indicates presence of speed bump or hump in a nearby location.

Crossing: A POI annotation which indicates presence of crossing in a nearby location.

Give_Way: A POI annotation which indicates presence of give_way sign in a nearby location.

Junction: A POI annotation which indicates presence of junction in a nearby location.

No_Exit: A POI annotation which indicates presence of no_exit sign in a nearby location.

Railway: A POI annotation which indicates presence of railway in a nearby location.

Roundabout: A POI annotation which indicates presence of roundabout in a nearby location.

Station: A POI annotation which indicates presence of station (bus, train, etc.) in a nearby location.

Stop: A POI annotation which indicates presence of stop sign in a nearby location.

Traffic_Calming: A POI annotation which indicates presence of traffic_calming means in a nearby location.

Traffic_Signal: A POI annotation which indicates presence of traffic_signal in a nearby location.

Turning_Loop: A POI annotation which indicates presence of turning_loop in a nearby location.

**Period-of-Day (4):**

Sunrise_Sunset: Shows the period of day (i.e. day or night) based on sunrise/sunset.

Civil_Twilight: Shows the period of day (i.e. day or night) based on civil twilight.

Nautical_Twilight: Shows the period of day (i.e. day or night) based on nautical twilight.

Astronomical_Twilight: Shows the period of day (i.e. day or night) based on astronomical twilight.

# Report & Conclusion

Analysis tells that majority of accidents have severity ~2 means not much higher impact on traffic.

in approx 75% cases no precipitation was recorded so this could mean rain is not the reason for accidents.

on an avg accidents happen even while the visibility is ~9 miles so this could mean that visibility is not a reason.

average length of the road extent affected by the accident is 7 miles.

Miami(CITY) had most no of accident cases i.e 106966

Top 5 Cities which had most number of cases are

Miami 106966 Los Angeles 68956 Orlando 54691 Dallas 41979 Houston 39448 Cities which had least no of accidents are

Ridgedale 1 Sekiu 1 Wooldridge 1 Bullock 1 American Fork-Pleasant Grove 1 CA (STATE) had most no of accident cases i.e 795868

Top 5 States of US which had most no accident cases are:

CA 795868 FL 401388 TX 149037 OR 126341 VA 113535 US/Eastern timezone region reported the most number of accident cases.

I-95 N street had max accident cases i.e 39853

Most accident occurs between 2:00PM - 6:00PM

most-deadliest accident hour is 5:00PM

next highest accident occur between 7:00AM - 8:00AM

friday had the highest no of accident cases i.e 492074.

accident cases are less during weekends i.e satuday and sunday and evenly distributed during business days.

Most no of cases are occured during December i.e 473943

at the end of the year the number of accidents is quite high ie during december,november,october had most no of accidents

year 2021 had max no of accidents i.e 1511745

trend is increasing exponentially yearly . sharp rise after year 2020.

maximum no of cases occured between temperature range: 50-80 F.

maximum no of cases occured between humidity range: 80-100 %.

as the humidity increases the no of cases also increases.

Maximum cases occured for the wind speed range between 5(mph) - 10(mph)

This is normal wind speed hence it is not the reason for accidents.

max no of accident occured when the air pressureis between 20(in) to 30(in).

30(in) had max accidents

Weather condition was Fair in most of the cases hence it is not a major cause behind the accidents.


