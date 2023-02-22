# APIs

### Summary of Why Reading are Relevant

## Readings
### [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
1. What does REST stand for?
> Representational State Transfer (REST)
  - (Copied from Reading)
2. REST APIs are designed around a ____.
  - Resources
3. What is an identifier of a resource? Give an example.
> URI: https://adventure-works.com/orders/1
4. What are the most common HTTP verbs?
> GET retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.
> POST creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger operations that don't actually create resources.
> PUT either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.
> PATCH performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.
> DELETE removes the resource at the specified URI.
  - (Copied from Reading)
5. What should the URIs be based on?
> nouns (the resource) and not verbs (the operations on the resource).
  - (copied from reading)
6. Give an example of a good URI.
> https://adventure-works.com/orders // Good
  - (Copied from Reading)
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
  - APIs that expose a lot of small resources
8. What status code does a successful `GET` request return?
  - 200
9. What status code does an unsuccessful `GET` request return?
  - 404
10.  What status code does a successful `POST` request return?
  - 201
11. What status code does a successful `DELETE` request return?
  - 204


### Things I want to know more about:
  -
