# NYC Last Mile Transit Dataset

## Summary

### Folders

| Primary Folder | Content |
| ------------- | ------------- |
| Output_max_n_stops_i | Dataset with the following setting: maximum number of stops in routes = i  |

| Secondary Folder | File | Description|
| ------------- | ------------- | ------------- |
| A_jk_CSV | A_jk_station_i.csv| matrix of routes for LM station i, size = [number_of_routes x number of stops (stop zero is always the LM station)], a_jk=1 if stop j is on route k |
| N_ijd_CSV | N_ijd_station_i_stop_j_day_d.csv| Demand data for station i, stop j, on day d, rows (19 time intervals): demand at the current time interval | 
| n_stats_ijt_CSV | n_stats_ijt_station_i_stop_j.csv| Summary Statistics for the demand data, rows (19 time intervals): demand of each time interval/ columns (4 statistics): statistics of demand during a time interval [MAX,MIN,MEAN,VAR] computed over 30 day data|
| T_ijk_CSV | T_ijk_station_i.csv | Service time matrix for stop i on route j for [LM station i] (unit: minutes) |
| T_ik_CSV | T_ik_station_i.csv | Total travel time of routes for [LM station i] (unit: minutes) |



