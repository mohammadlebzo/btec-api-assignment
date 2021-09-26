# Investigating APIs (Q2.1)

## LocationIQ API

### API Description

Its an *API* that offers **Geocoding**, **Maps** and **Routing** for users.

### API Usage

This *API* was used to *retrieve* **map images** according to the **longitude and latitude data** that was collected from the **WeatherBit API** so we can *render* it all to the user.

### API Endpoints/Request URLs

`https://maps.locationiq.com/v3/staticmap?key=<<key>>&center=<<latitude info>>,<<longitude info>>&zoom=<<zoom level: 1-16>>`

### Authentication Key

**Authentication Key**: pk.6685bf97d292b521b5835cb17f4fcf36

## WeatherBit API

### API Description

Its an *API* that allows it's users to *retrieve* the data of **current weather observations** from thousands of *wather stations*, also they can retrieve **historical weather data for the past 10+ years**, and some **highly localized weather forcasts** for any point of the globe.

### API Usage

This *API* was used to retrieve the **forecast data** for the **next 6 days**, also the **longitude and latitude data** for that place in order to **render it in a table** and show it to the user.

### API Endpoints/Request URLs

`https://api.weatherbit.io/v2.0/forecast/daily?key=<<key>>&city=<<city name>>`

### Authentication Key

**Authentication Key** = 2d779f50d54a4a88835b3d962d75c9c0

## TheMovieDB API

### API Description

Its an *API* that **offers data and/or images of movies, TV shows and actors**.

### API Usage

This *API* was used to *retrieve data* of **movies** that **containe the entered query keyword within its properties** to *render* it's data in *cards* and show them to the user.

### API Endpoints/Request URLs

`https://api.themoviedb.org/3/search/movie?api_key=<<api_key>>&query=<<keyword>>`

### Authentication Key

**Authentication Key** = 44d7e5b985c13f05c6230b397a75ac68

## Application Live Link (City Explorer Live Link)

- Live Link: [https://city-explorer-301d33-19013778.netlify.app](https://city-explorer-301d33-19013778.netlify.app)

- My Back-End GitHub Repo Link (city-explorer-api): [https://github.com/mohammadlebzo/city-explorer-api](https://github.com/mohammadlebzo/city-explorer-api)
- My Front-End GitHub Repo Link (city-explorer): [https://github.com/mohammadlebzo/city-explorer](https://github.com/mohammadlebzo/city-explorer)

## References

- LocationIQ: [https://locationiq.com/docs](https://locationiq.com/docs)
- WeatherBit: [https://www.weatherbit.io/api](https://www.weatherbit.io/api)
- TheMovieDB: [https://www.themoviedb.org/documentation/api](https://www.themoviedb.org/documentation/api)
