# Readings: APIs
 ## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design) 🤓

1. What does REST stand for?
 REST is an architectural style for building distributed systems based on hypermedia*

2. REST APIs are designed around a __resources__.

3. What is an identifer of a resource? Give an example.
which is a URI that uniquely identifies that resource
https://adventure-works.com/orders/1

4. What are the most common HTTP verbs?
GET, POST, PUT, PATCH, and DELETE.

5. What should the URIs be based on?.
 uniquely identifies that resource

6. Give an example of a good URI.
the URI for a particular customer order might be:
{"orderId":1,"orderValue":99.90,"productId":1,"quantity":1}


7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
 web APIs that expose a large number of small resources/ bad thing

 8. What status code does a successful GET request return?
  tatus code 200 (ok)


9.  what status code does an unsuccessful GET request return?
status code 404 (Not Found)

10. what status code does a successful POST request return?
status code 201 (Created)

11. What status code does a successful DELETE request return?
status code 204 (deleted)
