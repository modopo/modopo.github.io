# Reading Class 12

Status Codes for REST Methods

1) 100s = The header is sent and the server will try and accommodate the demand from the client side.
200s = Success codes, where the server successfully accepted the client's request.
300s = Redirects, letting the client know the data is no longer here and may need to be requested elsewhere
400s = Invalid requests sent to the server 
500s = Server error codes, which often indicate the server is having issues, not the client sided

2) 202 indicates the status was requested but the processing has not been completed.

3) 308 indicates the resource requested has been moved to the URL given the location header.

4) 204 status code

5) 410 status code

6) 403 status code

Build A REST API With Node.js, Express, & MongoDB

1) .env is used to keep access keys from being used by malicious actors.

2) Middleware is code that handles the request between the server and the intended route.

3) `app.use(express.json())` parses incoming request into JSON instead of a response element.

4) The colon denotes a parameter. When the route is matched in parameters, the value would be the id.

5) PUT is altering resources when the client sends data that revamps the whole resource. PATCH is atransforming the resources when the client transmits partial data that will be updated without changing the whole data.

6) You set a default value in the property.

7) A 500 status means the server encountered something unexpected and could not fulfill the request.

8) 200 means the request has succeeded, while 201 is request has succeeded and a new resource has been created. 

## Things I want to know more about