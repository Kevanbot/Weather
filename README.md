# Weather
simple weather app.
/*
const key:string = 'e634c0a0bce9e09bc2c9f8ccf2354a66';
let userrequest = require('prompt-sync')({sigint: true});
let cityname:string = 'austin';
const url = `https://api.openweathermap.org/data/2.5/weather?q=${cityname}&appid=${key}`
const headers = 


(async function () {
    const response = await fetch( url.toString(), {headers} );
    const data = await response.json();
    console.log(data)
  })()
*/
fetch('`https://api.openweathermap.org/data/2.5/weather?q=austin&appid=e634c0a0bce9e09bc2c9f8ccf2354a66')
  .then(response => response.json())
  .then(json => console.log(json))








/*example of api response
{
    "coord": {
      "lon": -122.08,
      "lat": 37.39
    },
    "weather": [
      {
        "id": 800,
        "main": "Clear",
        "description": "clear sky",
        "icon": "01d"
      }
    ],
    "base": "stations",
    "main": {
      "temp": 282.55,
      "feels_like": 281.86,
      "temp_min": 280.37,
      "temp_max": 284.26,
      "pressure": 1023,
      "humidity": 100
    },
    "visibility": 16093,
    "wind": {
      "speed": 1.5,
      "deg": 350
    },
    "clouds": {
      "all": 1
    },
    "dt": 1560350645,
    "sys": {
      "type": 1,
      "id": 5122,
      "message": 0.0139,
      "country": "US",
      "sunrise": 1560343627,
      "sunset": 1560396563
    },
    "timezone": -25200,
    "id": 420006353,
    "name": "Mountain View",
    "cod": 200
    }                         
  */
                          
