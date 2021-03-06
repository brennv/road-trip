# road-trip

Methods for using genome algorithms to calculate optimal road trips as demonstrated by [rhiever](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/optimal-road-trip).

## Usage

Obtain a [google maps api key](https://console.developers.google.com), install requirements and run the script.

```
virtualenv -p python2 env
source env/bin/activate
pip install -r requirements.txt
export GOOGLE_MAPS_API_KEY=your-api-key

python trip.py
```

## Results

See output maps:

https://rawgit.com/brennv/road-trip/master/Output_1.html

https://rawgit.com/brennv/road-trip/master/Output_33138793.0.html

## Locations

The list of waypoints can be changed in [trip.py](https://github.com/brennv/road-trip/blob/master/trip.py#L20):

- New York New York
- Atlanta Georgia
- Chicago Illinois
- Washington DC
- Philadelphia Pennsylvania
- Miami Florida
- Houston Texas
- Detroit Michigan
- Dallas Texas
- Los Angeles California
- Baltimore Maryland
- Memphis Tennessee
- Norfolk Virginia
- St. Louis Missouri
- San Francisco California
- Charlotte North Carolina
- Cleveland Ohio
- New Orleans Louisiana
- Richmond Virginia
- Orlando Florida
- Boston Massachusetts
- Tampa Florida
- Riverside California
- Birmingham Alabama
- Jacksonville Florida
