# MRT Distance printer
inputs block list & outputs distance to the MRT and minutes to the MRT by walking

### Steps:
1. Wiki scrap: scrap wiki for MRT and LRT names 
2. mrt_lat_long: get lats and longs for each station using onemap (a Singaporean map app)
3. Haversinne distance: use haversine distance to calculate the distance between the blocks, in this case condos, to the nearest MRT station and estimate walking speed to be 75m/min for an average Singaporean