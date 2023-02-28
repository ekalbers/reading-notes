# CRUD

## Readings
### [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
1. In your own words, describe what each group of status code represents:
  - 100: information codes
  - 200: Success codes; request was accepted, met all validation requirements
  - 300: Redirection Codes; the resource being requested isnt available at the given location anymore
  - 400: Client Error; Client sends some type of incorrect input
  - 500: Server Error; something is wrong with the server
2. What is a status code 202?
  - asynchronous processing request
3. What is a status code 308?
  - The resource is available at a new location and the client should directly access it via new URL in the future.
4. What code would you use if an update didn’t return data to a client?
  - 202
5. What code would you use if a resource used to exist but no longer does?
  - 410
6. What is the ‘Forbidden’ status code?
  - above 599

## Videos
### [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - because when the server is deployed it will not use localhost
2. What is middleware?
  - code that runs when the server gets a request but before it gets to routes
3. What does `app.use(express.json())` do?
  - allows server to accept json as the body
4. What does the `/:id` mean in a route?
  - specifies that there is a parameter that can be accessed by `request.params.id`
5. What is the difference between `PUT` and `PATCH`?
  - put creates a whole new object, patch updates an existing object
6. How do you make a default value in a schema?
  - makke a `default:` property
7. What does a `500` error status code mean?
  - server error
8. What is the difference between a status `200` and a status `201`?
  - 200: everything was successful, 201: creation was successful

