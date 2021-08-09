# Reading
## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

In your own words, describe what each group of status code represents:

100’s = Informational status codes, the header part of the request has been received, but it won't success.
200’s =Success codes. meaning it will respond with what the user asked.
300’s =Redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore
400’s =Error codes. They happen when the user send invalid request like timeouts, wrong URI, missing authentication, etc
500’s =Server error codes. 

What is a status code 202?

DELETE() : When using delete action. If the deletion is asynchronous and takes some time, which is the case in distributed systems, it can be appropriate to return this code with some information or URL to tell the client when it will be deleted.

PUT() or PATCH() : When trying to make an update, and If the update is done asynchronous, this code can be used. It should include an URL to access the updated resource or an URL to check if the update has been succeeded. It can also include an estimation of how long the update will take.



POST() : When trying to create an action, and it is accepted this code appears.


What is a status code 308?

API change : This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. The current endpoint can’t control the clients’ behavior after the request and a subsequent redirect if the resource URL changes again have to be issued from the new URL.

Multiple Endpoints for One Resource : If we have nested resources /user/kay/comments/456 and /posts/123/comments/456; and a root resource /comments/456 it can make things easier to simply issue 308 redirects at the nested resources with the Location header field pointed to the root resource so not every endpoint needs a delivery implementation. This should only be done for GET requests.

Wrong URL: If the URL the user used is wrong. This would be the right code if we know that a resource has moved to a different URL and we can tell the client about it.


What code would you use if an update didn’t return data to a client?

204 No Content : For updates that don’t return data to the client, for example when just saving a currently edited document.

What code would you use if a resource used to exist but no longer does?

404 : This code is what is used mostly when a resource is not existing. It also can be used in different situations, like when a resource exist, but due too security measures we can't give access to the user.

What is the ‘Forbidden’ status code?
The Forbidden status code, which is 403 is given whenever the user can not get access to a resource. Wether the user is authorized or not

