# Error codes

The response status returned is indicative of the results of the call. Common codes returned by the API include:
- 200 - Success!
- 201 - Created
- 202 - We received your request and queued it for asynchronous processing
- 204 - Success, but there is no response body
- 400 - Bad Request. Errors will be listed in the response body.
- 403 - Not Authorized. Your API-KEY was missing or invalid
- 404 - Not Found. The business or other entity you requested could not be found.
- 422 - Unprocessible Entity. Errors were found in the data being processed. Errors will be included in the response body.
- 500 - Server Error. Houston, we have a problem!