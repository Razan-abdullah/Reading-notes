
# API Design Best Practices

---


## 1-What does REST stand for?

REST is an acronym for REpresentational State Transfer and an architectural style for distributed hypermedia systems.

## 2-REST APIs are designed around a ____.


## 3-What is an identifier of a resource? Give an example.
The target of an HTTP request is called a "resource", whose nature isn't defined further; it can be a document, a photo, or anything else. Each resource is identified by a Uniform Resource Identifier (URI) used throughout HTTP for identifying resources.

EG: WWW.GOOGLE.COM

## 4-What are the most common HTTP verbs?

POST, GET, PUT, PATCH, and DELETE

## 5-What should the URIs be based on?

Rule #1: A trailing forward slash (/) should not be included in URIs
Rule #2: Forward slash separator (/) must be used to indicate a hierarchical relationship
Rule #3: Hyphens (-) should be used to improve the readability of URIs
Rule #4: Underscores (_) should not be used in URIs
Rule #5: Lowercase letters should be preferred in URI paths
Rule #6: File extensions should not be included in URIs
Rule #7: Should the endpoint name be singular or plural?


## 6-Give an example of a good URI.

example.com/articles/3252

## 7-What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource.


## 8-What status code does a successful GET request return?

 the request was successfully received, understood, and accepted



## 9-What status code does a successful POST request return?

 The status code 200 OK is used to indicate that a request was received, processed, and was successful. 


## 10-What status code does a successful DELETE request return?

The status should be 202 (Accepted) if the action has been queued.


--
# Reffrences 

-[RegExr](https://regexr.com/)
-[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
-[Regex 101](https://regex101.com/)