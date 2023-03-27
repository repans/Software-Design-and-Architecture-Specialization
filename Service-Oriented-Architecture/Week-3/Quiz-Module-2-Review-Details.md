# Module 3 Review Details 


------------------ 

### 01. REST uses several HTTP methods to communicate. Which HTTP method should not make a change to data on the server? 
```
GET
```

The HTTP method that should not make a change to data on the server is the GET method.

In the context of RESTful web services, the GET method is typically used to retrieve data from the server, without making any modifications to the data or the server state. The GET request is considered safe and idempotent, meaning that multiple identical requests can be made without affecting the server state or producing different results.

On the other hand, HTTP methods such as POST, PUT, PATCH, and DELETE are typically used to modify or delete data on the server. These methods are not considered safe and may have side effects on the server state, which is why they should be used with caution and proper authentication and authorization mechanisms in place.

------------------ 

### 02. Which of these are constraints of REST architectures? Choose the three correct answers.
  
a. **Clients can cache responses**   
b. **Uniform interface for communication**  
c. **Layered and client-server based**   
d. Interactions rely on state 

Explanation:

These three options are the correct constraints of REST architectures:

  a. Clients can cache responses: REST architectures are designed to be cacheable. Clients can cache responses to improve performance and reduce the number of requests made to the server.

  b. Uniform interface for communication: REST architectures use a uniform interface for communication between clients and servers. This interface includes standard HTTP methods (GET, POST, PUT, DELETE), resource URIs, and hypermedia as the engine of application state (HATEOAS).

  c. Layered and client-server based: REST architectures are based on a client-server architecture, where the client and server are separated by a network. The architecture is also layered, which means that each layer can only see and interact with the layer directly below it.

------------------ 

### 03. According to REST best practices, where should you specify what format the input and output messages are in?
  
a. Parameters in the URI   
b. **HTTP headers**  
c. XML schema   
d. sub-resources in the URI 

According to REST best practices, the format of input and output messages should be specified in the HTTP headers.

HTTP headers are used to convey additional information about the request or response, including the content type of the message body. The content type header specifies the format of the data being sent or received, such as JSON or XML. By using the content type header, clients and servers can communicate in a standardized way about the format of the messages being exchanged.

Parameters in the URI are used to identify specific resources and operations, but they do not convey information about the format of the data. XML schema is a specific technology used for describing the structure of XML data, but it is not the preferred way to specify the format of messages in RESTful web services. Sub-resources in the URI are used to represent relationships between resources, but they also do not convey information about the format of the messages being exchanged.

------------------ 

### 04. Which of these are acceptable REST URIs according to best practices? Choose the two correct answers.
  
a. **/students/**  
b. **/students/3/**   
c. /student/   
d. /getstudent/

The two correct URIs according to RESTful best practices are:

  a. /students/
  b. /students/3/

Explanation:

According to RESTful best practices, URIs should be designed to identify resources, not actions or operations. The URIs should represent resources as nouns, and avoid using verbs or operation names in the URI. The URIs should also be consistent and predictable, following a hierarchy or nesting structure that reflects the relationships between resources.

Option a, "/students/", represents a collection of all students and is a valid resource identifier.

Option b, "/students/3/", represents a specific student with an ID of 3, which is also a valid resource identifier.

Option c, "/student/", is not a good resource identifier because it does not specify a particular student. It is too vague and could represent many resources.

Option d, "/getstudent/", is not a good resource identifier because it uses a verb ("get") to describe an action or operation, which is not recommended in RESTful design.

------------------ 

### 05. Which of these is NOT used in developing RESTful web services?
  
a. JSON  
b. simple text  
c. XML  
d. **SOAP** 

SOAP is NOT used in developing RESTful web services.

Explanation:

SOAP (Simple Object Access Protocol) is a protocol used for exchanging structured information between applications over the internet. SOAP is not part of RESTful web services architecture, which is based on the use of HTTP and a set of architectural constraints to create scalable web services.

RESTful web services are typically developed using simple text formats like JSON (JavaScript Object Notation) and XML (Extensible Markup Language) for data exchange between the client and the server. These formats provide a lightweight, human-readable way to exchange data that can be easily parsed by different programming languages and technologies.

While SOAP is not used in RESTful web services, it is used in other web service architectures, such as SOAP web services. However, SOAP is often considered more complex and heavyweight compared to RESTful web services, and may not be as well-suited for lightweight, scalable web services.

------------------ 

### 06. By convention, which HTML method is usually used to create a new resource?
  
a. PATCH   
b. DELETE   
c. **POST**  
d. PUT 

By convention, the HTTP method that is usually used to create a new resource in RESTful web services is POST.

Explanation:

According to the RESTful design principles, HTTP methods should be used to indicate the intent of a client's request. The four most commonly used HTTP methods in RESTful web services are:

GET - retrieves a representation of a resource
POST - submits an entity to a resource, often causing a change in state or side-effects
PUT - replaces or updates a resource with a new representation
DELETE - removes a resource
By convention, POST is used to create a new resource on the server, while PUT is typically used to update an existing resource. So, when a client wants to create a new resource on the server, it should send a POST request to the appropriate URI with the necessary data in the request body. The server will then create a new resource with the provided data and return a response containing the new URI for the created resource.

------------------ 

### 07. What is the recommended way to not break functionality if your RESTful API is being used by many users?
  
a. Refactor the service, keeping the API the same   
b. Describe your service with WSDL  
c. Subscribe your service consumers to change notifications  
d. **version your API** 

The recommended way to not break functionality if your RESTful API is being used by many users is to version your API.

Explanation:

As your RESTful API evolves and new features are added or existing features are changed, it is important to ensure that existing clients continue to function as expected. Versioning your API involves creating a new version of the API that is backward-compatible with previous versions. This allows clients to continue using the old version of the API while also providing a path for them to migrate to the new version as needed.

Versioning can be done in a number of ways, including using a version number in the URI (e.g., "/v2/students"), using custom HTTP headers, or using a subdomain (e.g., "api.v2.example.com"). By versioning your API, you can add new features, fix bugs, and make other changes without breaking existing clients or forcing them to update their code immediately.

Refactoring the service while keeping the API the same may not be possible or practical, especially if the changes are not backward-compatible. Describing your service with WSDL is a practice used in SOAP web services, but not in RESTful web services. Subscribing service consumers to change notifications can help them stay informed about changes, but it does not necessarily prevent breaking changes.

------------------ 

### 08. Which of these best describes microservices?
  
a. Web service architectures consisting of lots of small, modular services  
b. **a variation of SOA applied on an application scale**  
c. Migrating business functionality into a set of services incrementally instead of all at once   
d. Replicating services and modifying them to fill other roles 

The correct answer is 
  b. Microservices are a variation of SOA applied on an application scale. 
They are a way of developing software applications as a suite of small, independently deployable services that communicate with each other over the network using standard protocols. Each microservice focuses on a specific business capability and can be developed, deployed, and scaled independently of other services.

------------------ 

### 09. Consider the two statements. Choose the one correct option.

  1. Microservices must be in the same language and framework
  2. Microservices can be replicated for scaling
  
a. Only the first statement is true  
b. **Only the second statement is true**   
c. Both statements are true  
d. Neither statement is true 

The first statement is incorrect, as microservices can be written in different languages and use different frameworks. The second statement is true, as replicating microservices is a common way to scale them horizontally.

------------------ 

### 10. Which are the advantages of microservices? Choose the two correct answers.
  
a. Testing is simple   
b. Performance is very good   
c. **Small teams can develop microservices quickly**   
d. **Services can be scaled independently**

The advantages of microservices are:

  c. Small teams can develop microservices quickly 
  d. Services can be scaled independently

Explanation:

a. Testing is simple: Although microservices have well-defined boundaries and independent deployment, testing them can become more complex than testing a monolithic application. So, this statement is not a correct advantage.

b. Performance is very good: The performance of microservices depends on the specific implementation and architecture, and is not necessarily better or worse than monolithic applications. So, this statement is not a correct advantage.

c. Small teams can develop microservices quickly: Microservices are typically designed to be small, focused, and independently deployable, making it easier for small teams to develop them quickly and efficiently.

d. Services can be scaled independently: Microservices can be independently deployed and scaled, which means that the infrastructure resources can be allocated efficiently based on the demand. This also allows better fault tolerance and availability of the service.

Therefore, the correct advantages of microservices are c and d.

------------------ 

### 11. How can you pass parameters in a REST call? Select the two correct answers.
  
a. In the SOAP header   
b. **In XML**   
c. In the HTTP header   
d. **In the URL** 

------------------ 

### 12. Consider the following two statements about RESTful web services. Choose the one correct option

  1. Requests can be sent in simple text
  2. PUT is usually used to create a new resource
  
a. **Only the first statement is true**  
b. Only the second statement is true   
c. Both statements are true  
d. Neither statement is true  



------------------ 
