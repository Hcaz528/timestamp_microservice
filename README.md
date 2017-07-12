# Freecodecamp Timestamp Microservice

I have completed the Timestamp Microservice for freecodecamp as part of obtaining a backend develoment certification

## What my Timestamp Microservice can do
* It can provide you with both the UNIX time since 1970 and the current date in a natural form
* Just supply a correctly formatted query into the url for the service to do it's magic
---
### See examples of correctly formatted urls below
* `https://url/December%2015,%202015`
* `https://url/1450137600`
* `https://url/December 15, 2015`
* `https://url/December 15 2015`
* `https://url/December152015`
---
### Example Output
`{ "unix": 1450137600, "natural": "December 15, 2015" }`