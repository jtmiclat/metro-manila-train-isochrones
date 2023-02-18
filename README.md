# Metro Manila Train Isochrones
Data Processing for https://felt.com/map/Where-can-you-reach-if-you-walk-for-15-mins-from-a-train-station-6T5pTwLVQNyVLL49CFfvXlB 


## Notes
Manualy got MRT, LRT1, and LRT2 train station points and saved to the following geojson.
```
data/mrt.geojson
data/lrt1.geojson
data/lrt2.geojson
```

Got the isochrones for each station using [Open Routes Services](https://openrouteservice.org/). These are then saved to
```
data/mrt_isochrones.geojson
data/lrt1_isochrones.geojson
data/lrt2_isocrhones.geojson
```

Manipulated the data to remove the overlapping areas and save into a single file
```
data/final.geojson
```