# URL-Shortener
URL Shortener Microservice for FreeCodeCamps API-Projects

## User Stories
- I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.  
- If I pass an invalid URL that doesn't follow the valid `http://www.example.com` format, the JSON response will contain an error instead.  
- When I visit that shortened URL, it will redirect me to my original link.

## How to create a new shortened URL:
```
https://shortthis.herokuapp.com/new/https://www.google.com
```
### Output:
```
{
    originalURL:    https://www.google.com/,
    shorthandURL:   https://shortthis.herokuapp.com/UfT
}
```

## Visit the shortened URL:
```
https://shortthis.herokuapp.com/UfT
```
