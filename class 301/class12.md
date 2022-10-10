#  CRUD

Below you will find some reading material, code samples, and some additional resources that support today's topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

   100’s - Informational codes used to relay information between client and server during a request. Example 100 code: The server received the request headers and determined the client is okay to continue sending the request body.
   200’s - success codes. These indicate that the request issued was successfully fulfilled.
   300’s - redirect codes. These codes are used to tell the browser or server that some other action needs to take place to complete the previous request.
   400’s - client errors. These indicates an error on the requesters behalf.
   500’s - server errors. These indicates an error on the servers behalf.

1. What is a status code 202?

202 Accepted response status code indicates that the request has been accepted for processing, but the processing has not been completed

1. What is a status code 308?

308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers

1. What code would you use if an update didn't return data to a client?


204 No Content

1. What code would you use if a resource used to exist but no longer does?

It's used when the server knows that the requested URI used to refer to a resource, but no longer does. The server doesn't know any new URI for the resource; if it did, it would send a 301 (“Permanent Redirect”).

1. What is the 'Forbidden' status code?


403

## Videos

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw) - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

to make it secure

1. What is middleware?

Middleware is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.

1. What does `app.use(express.json())` do?

It parses incoming JSON requests and puts the parsed data in req.Dec 20, 2021


1. What does the `/:id` mean in a route?

Route parameters are named URL segments that are used to capture the values specified at their position in the URL


1. What is the difference between `PUT` and `PATCH`?


PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

1. How do you make a default value in a schema?

Your schemas can define default values for certain paths. If you create a new document without that path set, the default will kick in.

1. What does a `500` error status code mean?

the server encountered an unexpected condition that prevented it from fulfilling the request


1. What is the difference between a status `200` and a status `201`?

<!-- ### Bookmark and Review

PLACEHOLDER -->
