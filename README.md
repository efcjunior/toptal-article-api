# toptal-article-api
Building a Node.js/TypeScript REST API 

Source: https://www.toptal.com/express-js/nodejs-typescript-rest-api-pt-1

Thanks to https://www.toptal.com/resume/marcos-henrique-da-silva

# Module responsabilities

Route configuration to define the requests our API can handle

Services for tasks such as connecting to our database models, doing queries, or connecting to external services that are required by the specific request

Middleware for running specific request validations before the final controller of a route handles its specifics

Models for defining data models matching a given database schema, to facilitate data storage and retrieval

Controllers for separating the route configuration from the code that finally (after any middleware) processes a route request, calls the above service functions if necessary, and gives a response to the client