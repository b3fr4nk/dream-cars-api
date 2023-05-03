# dream-cars-api

an api to store your dream cars and look at other people's dream cars

## How to use

### To get info about a car

Send a get request to _____/cars/<make>/<model>/<year>

### To add a car to the database

Send a Post request to _____/cars containing the following in a JSON:
1. Make
2. Model
3. Model Year for specs provided
4. Horse Power
5. Weight
6. Drive type ie. AWD, FWD, RWD, 4WD
7. body style id. coupe, hatchback, truck, sedan etc.
8. number of doors

### To update your garage

send a PUT request to _____/<userid>/garage
