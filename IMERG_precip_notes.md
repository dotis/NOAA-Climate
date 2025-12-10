### Notes on NASA GPM IMERG products

1. Use "FINAL" products from ED Search (HD5 format)
2. "GIS" products are the same, but in GeoTIFF format
3. Units are mm/hr; need to multiply by number of hours/month to get total accumulation
4. This will be month dependent

Tasks:
1. Get monthly files from ED Search
2. Ingest, convert to total accumulation
3. Extract for JPK using json files for each NMS
4. Output to monthly .csv files (one file per sanctuary)
