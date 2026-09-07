This is a standard api test using Bruno, API testing tool.

For each request, it will be validated the following: 
* The request status, if it is either 200 or else.
* The response format, in this case we want responses to be JSON.
* The response time, it should be under 3 seconds.
* if the ticker exists and if the ticket matches variable. (made it in a way that will return 2 errors for ORDERUSDC request.) 
* if price is a valid positive number.
* And validate if currency exists.


It is just standard basic tests to validate the API functionality using BRUNO.
