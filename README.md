## Structure outline

![alt text](./images/diagram.svg)

## How to run the code

1. Clone the repository and ensure requirements are installed
2. Create the following folders:
    - data
    - data/id_mappings
    - data/objects
3. Get ahold of the following files/folders:
    - data/id_mappings/floorId_to_mapId.json
    - data/floorplans-main
    - data/zValue_to_pValue.json
    - .env
4. Run src/init.py
5. Run src/main.py to process 5 minutes of data from live data API

After the steps above one can:
- Run src/occupancy.py to convert and enrich refined_data.db to occupancy.db
- Run src/client_api.py to start the density map API app

## Todo / Suggestions / Extensions
- Generate data/zValue_to_pValue.json file in init.py
- Split init.py into init.py for first time running and update.py for pythagoras updates

- Elliptic position probability density function
- Approximate number of people from number of, say, smartphones

