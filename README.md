# API-testing
---

![API testing 1](https://github.com/GeoBaragan/API-testing/assets/167702080/f5060c96-8d06-4bd3-aa32-18e5cb35336b)

The uploaded image shows an API test conducted using Postman to obtain the weather forecast for the city of Sibiu from OpenWeatherMap. 

API URL: api.openweathermap.org/data/2.5/forecast?q=Sibiu,SB,+40&appid=50d24195b608e449483cdef62c4cadc7

q: Specifies the city for which the forecast is requested, in this case, "Sibiu, SB, +40".
appid: The API key required for authentication and access to the weather data.
HTTP Method: GET

Query Parameters:

q: Sibiu, SB, +40 - represents the city and its region code.
appid: 50d24195b608e449483cdef62c4cadc7 - unique API access key.

---
![API testing 3](https://github.com/GeoBaragan/API-testing/assets/167702080/054a527e-218b-430f-8c64-0c8618e8ec69)

The uploaded image shows an API test in Postman for reading data from a CRUD API.

API Endpoint: http://qachallenge.ro/api/test_api.php?action=fetch_all

HTTP Method: GET

Query Parameter:

action: fetch_all (specifies the action to fetch all records)
Response Details:

Status Code: 200 OK (successful request)
Response Time: 183 ms
Response Size: 3.45 KB

Contains a list of user records, each with the following fields:
id: User ID
first_name: First name of the user
last_name: Last name of the user

---
![API testing 2](https://github.com/GeoBaragan/API-testing/assets/167702080/2f580d36-72e4-47fb-819b-1ddf357c17f5)

The uploaded image displays an API test in Postman for fetching the weather forecast of Sibiu using OpenWeatherMap.

API Endpoint: api.openweathermap.org/data/2.5/forecast?q=Sibiu,SB,+40&appid=50d24195b608e449483cdef62c4cadc7&mode=json&units=metric

HTTP Method: GET

Query Parameters:

q: Sibiu,SB,+40 (specifies the city)
appid: 50d24195b608e449483cdef62c4cadc7 (API key)
mode: json (response format)
units: metric (units of measurement)

---

![API testing 4](https://github.com/GeoBaragan/API-testing/assets/167702080/3d27b23f-e866-4b41-a7c8-9d00cc793fcf)
The uploaded image shows an API test conducted using Postman to obtain the weather forecast for the city of Sibiu from OpenWeatherMap.

API URL: http://api.openweathermap.org/data/2.5/forecast?q=Sibiu,SB,+40&appid=50d24195b608e449483cdef62c4cadc7

q: Specifies the city for which the forecast is requested, in this case, "Sibiu, SB, +40".
appid: The API key required for authentication and access to the weather data.
HTTP Method: GET
Query Parameters:

q: Sibiu, SB, +40 - represents the city and its region code.
appid: 50d24195b608e449483cdef62c4cadc7 - unique API access key.






