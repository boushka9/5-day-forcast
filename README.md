# Five Day Weather Forcast

## Description
The purpose of this project was to create a basic weather forecaster using jQuery and the Open Weather API to render the current weather condition of any given city, along with an additional five day forecast. The app includes an input box to search for a city by name, a search history to display past searched cities, along with displays for the current and future weather conditions of those cites. The most difficult aspects of this project for me to accomplish were getting the city name from the input box and connecting that to the API, and rendering the weather data to the screen over a for lop. The first functionality was accomplished with a series of functions linked to a click event on the submit button. The second functionality is one that I plan to implement at a later date. Currently, the functionality to render current and future weather data was accomplished with individual elements/IDs in the html and setting the variables with the API data as the text content of those IDs. 

## Installation

No Installation is necessary to use this application. The deployed page can be accessed at https://boushka9.github.io/rainy-plastic-plants/.


## Usage

Access the deployed project at  https://boushka9.github.io/rainy-plastic-plants/ .

When the homepage loads, you will see search input along with the weather of the default city 'Austin', until a new city is searched. The main section of the page displays the current temperature, wind speed, and humidity in Austin Texas along with an icon representing the weather conditions. Similarly, the page displays five smaller weather cards below the current weather condition. Each card contains the temperature, wind speed and weather of the next five days, along with an icon representing the weather conditions.

<img src="./assets/imgs/full-page.png" alt="Search history and weather conditions displayed" width="300">

<img src="./assets/imgs/current.png" alt="Current weather conditions of Denver" width="300">  

<img src="./assets/imgs/card.png" alt="Future weather conditions of selected city" width="300" height="300">


As you search for the weather conditions in more cities, each city name that is inputed into the search section will appear below the search button. Up to ten city names can be displayed in the recently searched section. To see the conditions of one of your past searches again, simply click on the city name and it will be displayed. To clear your past search history, click 'Clear Past Cities'. 

<img src="./assets/imgs/city-history.png" alt="Search box and button, with search history below " width="300">


## License

MIT
