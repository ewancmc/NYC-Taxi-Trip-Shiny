# NYC-Taxi-Trip-Shiny

While Taxis are an incredibly important and useful mode of transport used by many, there is a lot of uncertainty regarding how much your trip will cost, when the best time to call is, and whether you will get to your destination on time. The total distance of your trip is strongly associated with the total fare, and the time the trip will take, however external factors such as traffic, road closures, and weather can all play a significant role in the strength of this association.

These datasets have been obtained from the NYC Taxi and Limousine Commission. Taxi trip data has been provided as a single PARQUET file (‘yellow_tripdata_2023-01.parquet’, see data dictionary for details), a taxi zone lookup table has been provided as a CSV file (‘taxi_zone_lookup.csv’), and a shape file has been provided for mapping purposes (‘taxi_zones.shp’).

The main limitation of this analysis is the brevity of the time period explored (Jan 2023), while approximately 3,000,000 yellow taxi trips were taken during this time, it is unclear whether this data can be used to make accurate predictions about taxi trips throughout the year. Further, there are some zones/airport combinations in which no taxi trips were taken in this period, resulting in an inability to make meaningful predicitons about taxi trips with these combinations of pickup zone and dropoff airport.

## Running analysis locally

1. Clone the repo
   ```sh
   git clone https://github.com/ewancmc/NYC-Taxi-Trip-Shiny
   ```
2. Run document (this will output a flexdashboard using the shiny runtime)

## Viewing analysis online

Full dashboard can be viewed [here](https://ewan-cmc.shinyapps.io/eto5510_assessment_2-1/)

