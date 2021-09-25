# White Box Testing (Q3.1)

## Back-End Testing

### 1. There should be an active Back-End server to call data from a 3rd party API
|Image|Description|
|-----|------|
|![server.js](./images/server_js.PNG)|*The Back-End server*|
|![test_route](./images/test_route.PNG)|*This is the back-end server that handels a couple of routes, to check if the server is active go to the route `/test`, and as you can see the back-end server is active*|

### 2. The server should retrieve data according to the query name from the 'WeatherBit' API when the '/weather' is called and send it as a response, holding the data of the name, latitude and longitude, also the weather forecast of the 6 upcoming days for that query name

|Image|Description|
|-----|------|
|![weatherModule](./images/weatherModule.PNG)|*Weather Module*|
|![weatherRoute](./images/weatherRoute.PNG)|*Calling the `/weather` (**the server will call the function associated with the call**) **ex**: `server.get('/weather',weatherRoute);`*|
|![passCityName](./images/passCityName.PNG)|*Calling the `/weather` and passing it the **query parameter** `city=Seattle`*|
|![weatherResult](./images/weatherResult.PNG)|*The **result** of the call. We got the **name**, **latitude** and **longitude**, also the **weather forecast as a JSON***|

### 3. The server should retrieve data according to the query name from the 'TheMOvieDB' API when the '/movies' is called and send it as a response, holding the data of the top movies in the area of the query name

|Image|Description|
|-----|------|
|![moviesModule](./images/moviesModule.PNG)|*Movies Module*|
|![moviesRoute](./images/moviesRoute.PNG)|*Calling the `/movies` (**the server will call the function associated with the call**) **ex**: `server.get('/movies',moviesRoute);`*|
|![passQuery](./images/passQuery.PNG)|*Calling the `/movies` and passing it the **query parameter** `query=london`*|
|![moviesResult](./images/moviesResult.PNG)|*The **result** of the call. We got the **title**, **overview**, **avarage_votes**, **total_votes**, **image_url**, **popularity** and **release date data as a JSON**|

### 4. All calls other than '/weather' and '/movies' should be handled

|Image|Description|
|-----|------|
|![allRoutesHandle](./images/allRoutesHandle.PNG)|*Handling all other routes. **code**: `server.get('*',anythingRout);` (**code at the main server.js**)*|
|![routeNotFound](./images/routeNotFound.PNG)|*When the route is anything except `/weather` and/or `/movies` the server will return `route is not found` and a `404` **status***|

### 5. All retrieved data should be cached to lower the number of hits on the 3rd party API server

### 6. Retrieved data should have a time stamp of the time that it was retrieved in

## Front-End Testing

<!-- |Image|Description|
|-----|------|
|![](./images/)||
|![](./images/)|| -->
