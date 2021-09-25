# White Box Testing (Q3.1)

## Back-End Testing

### There should be an active Back-End server to call data from a 3rd party API

*The Back-End server*:

<!-- <img src="./images/server_js.PNG"> -->
![server.js](./images/server_js.PNG)
This is the back-end server that handels a couple of routes, to check if the server is active go to the route `/test`:
![test_route](./images/test_route.PNG)
As you can see the back-end server is active.

### The server should retrieve data from the 'WeatherBit' API when the '/weather' is called and send it as a response

### The server should retrieve data from the 'TheMOvieDB' API when the '/movies' is called and send it as a response

### All calls other than '/weather' and '/movies' should be handled

### All retrieved data should be cached to lower the number of hits on the 3rd party API server

### Retrieved data should have a time stamp of the time that it was retrieved in

## Front-End Testing
