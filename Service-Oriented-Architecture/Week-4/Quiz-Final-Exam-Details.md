```
  # Do not copy if you are taking the test.
```
--- 

#  Final Exam Details 

---------------------- 

### 01. Marlon is creating a web page. It's a simple page, which has a list of his current projects, a short bio about himself, and some GIF images of some of those same projects that he uploaded to the server himself. What type of web page is this?
  
a. dynamic web page   
b. static web page   
c. web app   
d. web service  


---------------------- 
  
### 02. Which of these examples is a web application?
  
a. **online poker**  
b. a website conducting a survey   
c. an online shopping platform   
d. a blog   

Explaination: 
  b. Incorrect. Although surveys require user input, the web page itself is often static. A more complex survey may be dynamic. 
  c. Incorrect. Online shopping platforms are definitely dynamic, since they have to generate content (for example, showing your Shopping Cart with the items that you put in there), but they are not web applications. 
  d. Incorrect. 

---------------------- 
  
### 03. Which of these formats can be used to express and structure content to be sent over the internet? Choose the three correct answers:
  
a. JSON   
b. HTML   
c. CSS    
d. XML  


---------------------- 
  
### 04. What are the essential parts of an HTTP request? Choose the three correct answers.
  
a. a message body  
b. request-line   
c. a blank space   
d. headers 

Correct answers are: b, c, and d.

The three essential parts of an HTTP request are:

  b. Request-line: This specifies the HTTP method (e.g., GET, POST, PUT, DELETE), the URL of the resource to be requested, and the version of HTTP being used.
  c. A blank line
  d. Headers: These provide additional information about the request, such as the Accept and Content-Type headers.

Note that an HTTP request may or may not include a message body, depending on the type of request being made.

---------------------- 
  
### 05. Which of these are essential parts of an HTTP server response? Choose the two correct answers.
  
a. headers  
b. status-line   
c. a message body   
d. response-line  

There is no such thing as a "response-line" in HTTP. The correct term is "status-line". Therefore, the correct options are:

b. status-line
a. headers

---------------------- 
  
### 06. Consider the following two statements about Javascript. Choose the one correct option.

  1. It can allow you to generate content within the browser  
  2. A Javascript file must be sent in addition to an HTML file  
  
a. **Only the first statement is true**   
b. Only the second statement is true   
c. Both statements are true  
d. Neither statement is true  

Only the first statement is true.

Explanation:

  1. It can allow you to generate content within the browser: This statement is true. JavaScript is a programming language that can be used to create dynamic and interactive content within a web page. It runs in the browser and can be used to modify HTML and CSS, respond to user interactions, and make requests to servers.

  2. A Javascript file must be sent in addition to an HTML file: This statement is false. While it's common to include JavaScript code in a separate file that is loaded along with the HTML file, it is not strictly necessary. JavaScript code can also be included directly in the HTML file, within a <script> tag.  
  
---------------------- 
  
### 07. What is the term for the action  that converts the parameters into a standardized message on the client side?
  
a. invocation   
b. binding    
c. **marshalling**   
d. blocking  

  The term for the action that converts the parameters into a standardized message on the client side is *marshalling*.

---------------------- 
  
### 08. Consider the following two statements about middleware and RPC. Choose the one correct option.

  1. RPC (Remote Procedure Call) is a form of middleware  
  2. The IDL (Interface Definition Language) is responsible for generating stubs  
  
a. Only the first statement is true   
b. Only the second statement is true   
c. Both statements are true   
d. Neither statement is true  

The correct answer is (c) Both statements are true.

Explanation:

  - RPC (Remote Procedure Call) is a form of middleware that allows programs to call procedures or functions in other address spaces or processes. It provides a way for two programs to communicate with each other over a network, as if they were running on the same machine.
  - The IDL (Interface Definition Language) is a language used to define the interface that separates the client and the server in an RPC system. It defines the data types and functions that can be used by the client and the server, and it is responsible for generating the stubs and skeletons that are needed to make the RPC system work. 
  
---------------------- 
  
### 09. Which of these can be found in Common Object Request Broker Architecture (CORBA)? Choose the three correct answers.
  
a. facilities   
b. object request broker  
c. client and server stubs    
d. interface definition language  

  The correct answers are a, b, and d.

The correct answers are a, b, and d: facilities, object request broker, and interface definition language can all be found in Common Object Request Broker Architecture (CORBA). Client and server stubs are also part of the CORBA architecture, but they were not listed as one of the answer choices.
Though RPC architecture has stubs, CORBA replaces these with skeletons, which are like stubs except that they are proxy objects.
  
---------------------- 
  
### 10. What are some disadvantages of CORBA? Choose the two correct answers.
   
a. Implementation is difficult    
b. Objects are always called remotely   
c. Dynamic binding is impossible 
d. Clients and servers must be implemented in the same language   

The correct answers are a and b.
Although dynamic binding is difficult (not just in CORBA but in many architectures) it is possible!
Limited time and resources may make CORBA difficult to implement properly.

---------------------- 

### 11. In what format are SOAP messages represented?
  
a. HTML   
b. SOAP formatting is not based on any other format   
c. JSON   
d. XML 

SOAP messages are represented in XML format. 
  
---------------------- 

### 12. Which part of a SOAP message can be included but is NOT required?
  
a. envelope  
b. header  
c. HTTP method   
d. body  

The correct answer is (b) header. The header is an optional part of a SOAP message that can contain additional information about the message, such as security or routing details. 
  
---------------------- 

### 13. True or False: a SOAP message must be sent over HTTP.
  
a. True   
b. False

False. Although SOAP messages can be sent over HTTP, they can also be sent over other protocols such as SMTP or TCP. 
  
---------------------- 

### 14. Which type of description will a service requester need to bind to a web service?
  
a. WS-Description   
b. WSDL   
c. SOAP   
d. UDDI  

The correct answer is b. WSDL (Web Services Description Language) is a format for describing a web service that is used by service requesters to locate and bind to the service. 
  
---------------------- 

### 15. Which section of WSDL 2.0 contains concrete information like physical ports and mapping interfaces to endpoints?
  
a. interfaces   
b. bindings   
c. portTypes   
d. services  

The correct answer is (d) services. 
  
---------------------- 

### 16. What does the types section of a WSDL 2.0 document allow developers to do?
  
a. Define abstract data types   
b. Specify document-style or RPC-style interaction    
c. Specify which communications protocol is used (HTTP, SMTP…)   
d. Specifies the type of interaction (request-response, solicit-response…)  

The correct answer is (a.) Define abstract data types. The types section of a WSDL 2.0 document allows developers to define abstract data types, which can be used by messages, port types, and bindings. It provides a way to describe the data being exchanged in a web service operation, independent of any implementation details or programming language-specific syntax.

---------------------- 

### 17. Which aspects of web services does UDDI allow you to implement? Choose the two correct answers.
  
a. invocation   
b. publication   
c. discovery   
d. composition  

  The correct answers are (b.) publication and (c.) discovery. UDDI is a registry for web services that allows service providers to publish descriptions of their services, and service requesters to discover those services. 

---------------------- 

### 18. In which section of a UDDI description will you find information like the category of business and service?
  
a. blue pages   
b. green pages    
c. yellow pages  
d. white pages  

  The correct answer is c. yellow pages.

In a UDDI (Universal Description, Discovery and Integration) description, information like the category of business and service can be found in the yellow pages section. The yellow pages contain information about the service provider, including contact information and business category. The blue pages contain technical information about the service, such as its interface and binding details. The green pages contain information about the service’s quality of service (QoS) requirements. Finally, the white pages contain information about the UDDI registry itself. 

---------------------- 

### 19. Under which data structure of UDDI will you find a reference to the WSDL description?
  
a. businessEntity   
b. tModel   
c. businessService  
d. serviceInterface

The correct answer is b. tModel.  
  
In UDDI, a reference to the WSDL (Web Services Description Language) description can be found under the tModel data structure. A tModel is a technical model that describes a service type or a business entity. It contains information about the service’s interface and binding details. The tModel is used to define the service type and to provide a reference to the WSDL description. 
  
---------------------- 

### 20. What is the difference between coordination and composition in the context of services?
  
a. composition uses only objects 
b. coordination can only be done in a synchronous way   
c. composition exposes a combination of services as another service  
d. coordination is focused on pairwise interactions  

Service composition is a wider term that means services are coordinated to achieve some goal. However, this coordination can be performed in different ways. If there is a central coordinator, the service composition is a service orchestration. If there is no central coordinator, it is a service choreography.

From the given options, option 'c' is correct. Composition exposes a combination of services as another service.
  
---------------------- 

### 21. Consider the following two statements. Choose the one correct option.

  1. WS-BPEL only allows you to compose services out of basic services.
  2. WS-BPEL has other features such as conditional logic and the ability to store state.  
  
a. Only the first statement is true  
b. Only the second statement is true  
c. Both statements are true    
d. Both statements are false  

The second statement is true. WS-BPEL (Web Services Business Process Execution Language) has other features such as conditional logic and the ability to store state. WS-BPEL is a language for specifying business processes that use web services. It allows you to compose services out of basic services, but it also provides other features such as conditional logic and the ability to store state. Does that help?
  
---------------------- 

### 22. What does it mean that RESTful services are cacheable?
  
a. the service logic can be stored on the client   
b. the client can store a version of the server's response    
c. the server can store the state of the interaction    
d. the server can queue and prioritize requests  

The correct answer is (b) the client can store a version of the server's response.

In a RESTful service, responses from the server can include cache-control directives that indicate whether the response can be cached by the client or intermediate network devices. If a response is cacheable, the client can store a copy of the response and use it to satisfy future requests for the same resource, without needing to contact the server again. This can help to reduce network traffic and improve performance. 
  
---------------------- 

### 23. Which of these formats can be used within the invocation of a REST service? Choose the three correct answers.
  
a. simple text   
b. JSON  
c. XML    
d. WSDL  

The correct options are: a. simple text, b. JSON, and c. XML.

Explanation:
WSDL (Web Services Description Language) is not typically used in the invocation of a RESTful service, as it is associated more with SOAP-based web services. RESTful services can use a variety of data formats such as plain text, JSON (JavaScript Object Notation), and XML (eXtensible Markup Language). 
  
---------------------- 

### 24. Which of these is a good name for a REST resource? In other words, which of these resource names follow best practices? Choose the two correct answers.
  
a. /car/2   
b. /cars/2/tires    
c. /getCar/2   
d. /cars/2  

The correct answers are:

  d. /cars/2 
  b. /cars/2/tires

Explanation:

According to RESTful best practices, resource names should be plural and represent a collection of objects. Therefore, option a. "/car/2" should be changed to "/cars/2". Option c. "/getCar/2" should be avoided because it implies a remote procedure call rather than a RESTful resource. Option d. "/cars/2" is a good name for a resource representing a single car, while option b. "/cars/2/tires" represents a sub-resource of a car resource, in this case, the tires of car number 2. 
  
---------------------- 

### 25. You received an HTTP status code 201 from the server, which means that a resource was created. In a well-designed REST service, which HTTP methods did you send to the server?
  
a. GET  
b. POST   
c. PUT  
d. DELETE  

The HTTP method used to create a resource in a well-designed REST service is usually POST.  
So the correct answer is b. POST.  
  
---------------------- 

### 26. Which of these elements in the HTTP header of a request specifies the format of the response?
  
a. Host   
b. Content-Encoding:   
c. Accept:   
d. Content-Type:   

The correct answer is c. `Accept` header in an HTTP request specifies the format(s) that the client expects the response to be in, such as JSON, XML, or plain text.
  
---------------------- 

### 27. What is the most important difference between WS*-style web services (which utilize SOAP, WSDL, etc.) and RESTful web services?
  
a. Their differences are very minor  
b. RESTful services are simpler    
c. They do not use the same transfer protocol    
d. WS* are more secure  

  The correct answer is: b. RESTful services are simpler.  
The most important difference between the two is the architectural style they follow. WS*-style web services follow a more rigid and complex approach based on standards like SOAP, WSDL, and others. RESTful web services, on the other hand, follow a simpler and more flexible approach based on HTTP and other web standards, making them easier to develop and maintain. 
  
---------------------- 

### 28. Where are the formats of the input and output data specified, according to REST best practices?
  
a. In the HTTP request in XML format  
b. As parameters in the URL  
c. In the HTTP header    
d. In the HTTP request in JSON format  

Typically, the format of the input and output data is specified in the HTTP header using the Content-Type and Accept headers respectively. The Content-Type header specifies the format of the request payload, and the Accept header specifies the format that the client expects to receive in response. The formats themselves could be XML, JSON, or any other format that is agreed upon between the client and server.

So, the correct answer is:
  c. In the HTTP header

---------------------- 

### 29. What are some advantages of microservices architecture? Select the two correct answers.
  
a. Scaling through replication   
b. No centralized management   
c. Good performance  
d. Services can be developed in different languages 

  Two answers are a and d. 
  
Two advantages of microservices architecture are scaling through replication and services can be developed in different languages. Microservices architecture is a way of designing software applications as a collection of small, independent services that communicate with each other over a network. Each service is responsible for a specific task or function and can be developed and deployed independently of the other services. This makes it easier to scale the application by replicating the services that are under heavy load. It also allows developers to use different programming languages and frameworks for different services, which can improve productivity and reduce development time. 
  
---------------------- 

### 30. Consider the following two statements about microservices architecture. Choose the one correct option. 

  1. Communication between microservices is stateless
  2. Testing microservice architecture is complex
  
a. Only the first statement is true.  
b. Only the second statement is true.    
c. Both statements are true.  
d. Neither statement is true

Both statements are true. Communication between microservices is stateless, which means that each request and response is independent of any previous request or response. Testing microservice architecture can be complex because it involves testing multiple services that work together to provide a single application.

Therefore, option c is correct.
  
---------------------- 

--- 
> [Service-Oriented Architecture](https://www.coursera.org/learn/service-oriented-architecture/) {Week-4}
