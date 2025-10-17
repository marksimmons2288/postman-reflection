# postman-reflection
Weather Bit API

## Exploring the Weather API Assignment

## Request URL
The base url was https://api.weatherbit.io/v2.0 (had issues due to placing www. in the url which gave an error of invalid URI).

## Query Parameters Used
### 
1. api-key
2. postal_code
3. The reponse displayed an array of location, name, and city codes in summary.

## Importaance of correct query parameters
Using the incorrect parameters, from my experience, will cause the response to freeze and not display, as if it is continually searching for an output. (I tested zip_code instead of postal_code). The only solution I had was to exit out of the postman browser and attempt to GET again. This was the only way I could get the page to refresh.

