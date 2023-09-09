## Project Description:
In this project, we work as an analyst for a company, a new ride-sharing company launched in Chicago. Our task is to discover patterns in the available information. We want to understand passenger preferences and the impact of external factors on rides. Using the database, we analyze data from competitors and test hypotheses related to the influence of weather on ride frequency.

## Data:
Database containing taxi trip information in Chicago:
Table `neighborhoods`: data related to neighborhoods in the city of Chicago.

- _name_: Neighborhood names
- _neighborhood_id_: Neighborhood codes

Table `cabs`: Taxi data

- _cab_id_: Vehicle codes
- _vehicle_id_: Vehicle technical IDs
- _company_name_: Company names that own the vehicles

Table `trips`: Trip data

- _trip_id_: Trip codes
- _cab_id_: Operating vehicle codes
- _start_ts_: Start date and time of the trip (time rounded to the nearest hour)
- _end_ts_: End date and time of the trip (time rounded to the nearest hour)
- _duration_seconds_: Trip duration in seconds
- _distance_miles_: Trip distance in miles
- _pickup_location_id_: Pickup neighborhood code
- _dropoff_location_id_: Drop-off neighborhood code

Table `weather_records`: Weather Data

- _record_id_: Weather record code
- _ts_: Date and time when the weather record was taken (time rounded to the nearest hour)
- _temperature_: Temperature at the time of the weather recording
- _description_: Brief description of the weather conditions, such as "light rain" or "scattered clouds"
- 
## Libraries:
- _pandas_
- _requests_
- _BeautifulSoup_
- _matplotlib_
- _numpy_
- _scipy_
- _seaborn_
