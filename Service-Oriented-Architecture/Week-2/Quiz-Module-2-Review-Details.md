# Module 2 Review Details 

---------------------    

### 01. What standard is used for all aspects of web service development in this module, from describing interfaces to publishing and discovering services?
   
a. **XML**   
b. UDDI    
c. WSDL    
d. SOAP  

XML is used for all aspects of web service development in this module, from describing interfaces to publishing and discovering services. 

---------------------    

### 02. What are the two major styles of SOAP requests?
   
a. **RPC style**    
b. request-response   
c. **document style**    
d. envelope  

The two major styles of SOAP requests are:

  1. RPC (Remote Procedure Call) Style  
  2. Document Style  

Therefore, the correct answer is a and c, that is, "RPC style" and "document style."

In the RPC style, the SOAP request and response messages are structured like a typical remote procedure call. The message contains the name of the method being called, any parameters that need to be passed to the method, and a return value. This style is used when the web service is designed to expose a set of procedures or functions.

In the Document style, the SOAP message is structured as an XML document. The message can contain any data or information, including complex data structures. This style is used when the web service is designed to exchange complex documents or data between the client and server.

---------------------    

### 03. Which of these message patterns are typical of asynchronous messaging? Choose two correct answers.
   
a. **notification**   
b. **one-way**   
c. request-response    
d. solicit-response

The message patterns that are typical of asynchronous messaging are:

  1. Notification  
  2. One-way  

Therefore, the correct options are a. "notification" and b. "one-way".

In the notification pattern, the client sends a message to the server to inform it of an event, but does not expect a response.

In the one-way pattern, the client sends a message to the server and does not wait for a response. This pattern is useful when the client wants to send a message to the server, but does not need a response immediately.

In contrast, the request-response and solicit-response patterns are typical of synchronous messaging, where the client sends a request and waits for a response from the server.

---------------------    

### 04. Your web browser has an add-on that is alerted when your favourite blog has a new post. Which messaging pattern is this?
   
a. solicit-response   
b. **notification**     
c. request-response    
d. one-way 

The messaging pattern that is used when a web browser add-on is alerted about a new post on a blog is the "Notification" pattern.

Therefore, the correct option is b. "Notification."

In the notification pattern, a client sends a message to a server to inform it of an event, but does not expect a response. In this scenario, the web browser add-on is acting as the client and is sending a notification to a server that is responsible for monitoring the blog for new posts. When the server detects a new post, it sends a notification message to the web browser add-on to alert the user.

---------------------    

### 05. An important part of a WSDL (Web Service Description Language) file is a section that describes how services are invoked. For example, this section includes the style of interaction (document or RPC), the transport protocol, and how messages are turned into XML. What is this section?
   
a. **bindings**    
b. types    
c. interfaces    
d. services 

The section of a WSDL (Web Service Description Language) file that describes how services are invoked is called the "Bindings" section.

Therefore, the correct option is a. "Bindings."

The "Bindings" section of a WSDL file describes the details of how a web service is bound to a specific network protocol and message format. It specifies the communication protocol, message encoding, and transport details such as the HTTP method and URL for invoking the service. The bindings section also specifies the style of interaction (document or RPC) used by the service.

---------------------    

### 06. Consider the two statements. Choose the one correct option.

  1. SOAP messages can only be sent over HTTP
  2. Every SOAP message needs a header
   
a. Only the first statement is true   
b. Only the second statement is true    
c. Both statements are true    
d. **Neither statement is true**   

Both statements are false.

  1. SOAP messages can be sent over different transport protocols such as HTTP, SMTP, and TCP.
  2. While it is recommended to include a header in SOAP messages, it is not strictly required. A SOAP message can be sent with just a body.

---------------------    

### 07. Consider the two statements. Choose the one correct option

  1. WSDL can be used to describe non-XML based web services  
  2. A WSDL document can import other WSDL documents to gain access to their specifications  
   
a. Only the first statement is true   
b. Only the second statement is true    
c. **Both statements are true**    
d. Neither statement is true  

WSDL can be used to describe non-XML based web services such as RESTful services. The WSDL description can be used to define the available resources, their parameters, and the representations that can be requested or returned.

A WSDL document can import other WSDL documents to gain access to their specifications. This allows for modularity and reuse of service descriptions. 

---------------------    

### 08. UDDI covers two aspects of web service development. Which ones? Choose the two correct answers.
   
a. security    
b. composition    
c. **discovery**    
d. **publishing**  

The two aspects of web service development that UDDI (Universal Description, Discovery, and Integration) covers are "discovery" and "publishing."

Therefore, the correct options are c. "discovery" and d. "publishing."

UDDI is a platform-independent, XML-based registry that enables businesses to list their web services and discover other web services. The UDDI registry contains information about available web services, including their interfaces, protocols, and locations. The "publishing" aspect of UDDI refers to the process of adding information about a web service to the registry, while the "discovery" aspect of UDDI refers to the process of searching the registry for web services that meet specific criteria.

---------------------    

### 09. The green pages of UDDI contain which data structures? Choose the two correct answers.
   
a. **tModel**    
b. businessEntity   
c. **bindingTemplate**   
d. businessService 

In UDDI, the "green pages" are used to describe technical details of a web service. They contain data structures that specify the service's functionality, interface, and implementation.

tModel is a key part of UDDI that represents a technical model for the web service, providing information about the service implementation and interface, as well as any other relevant technical details.

bindingTemplate, on the other hand, is a data structure that provides concrete information about how to access the service. It specifies the endpoint, transport protocol, and message formats that are required to interact with the service.

Therefore, both tModel and bindingTemplate are part of the technical details that are included in the green pages of UDDI. 

---------------------    

### 10. Consider the following two statements. Choose the one correct option  

  1. Binding to a service is usually a run-time activity
  2. UDDI uses web services for publishing and discovering
   
a. Only the first statement is true   
b. **Only the second statement is true**    
c. Both statements are true   
d. Neither statement is true  
   
The statement "UDDI uses web services for publishing and discovering" is true, but the statement "Binding to a service is usually a run-time activity" is false.

Therefore, the correct option is b. "Only the second statement is true."

UDDI (Universal Description, Discovery, and Integration) is a platform-independent, XML-based registry that enables businesses to list their web services and discover other web services. UDDI uses web services for publishing and discovering, so the statement "UDDI uses web services for publishing and discovering" is true.

On the other hand, the statement "Binding to a service is usually a run-time activity" is false. The process of binding to a service involves establishing a connection to the service and defining the details of the communication, such as the message format and protocol. This process typically occurs during the development of the client application, rather than at run-time.

---------------------    

### 11. WS-BPEL covers what aspect of web services?  
   
a. security   
b. **composition**    
c. encryption    
d. publishing   

WS-BPEL covers the aspect of web services composition.

Therefore, the correct option is b. "Composition."

WS-BPEL (Business Process Execution Language for Web Services) is a standard for specifying the behavior of composite web services. It provides a language for describing complex business processes that involve multiple web services, and it defines a runtime environment for executing those processes. WS-BPEL is used to automate business processes by orchestrating the interactions between different web services, and it enables the creation of flexible and scalable composite applications.

---------------------    

### 12. Which part of a WSDL 2.0 description gives concrete information about the ports to be used for the service?  
   
a. bindings    
b. portTypes     
c. interfaces    
d. **services**   

The "port" element in the "service" section of a WSDL 2.0 description gives concrete information about the ports to be used for the service.

Therefore, the correct option is d. "services."

In WSDL 2.0, the "service" section describes a single web service and contains information about the ports that are available for that service. Each "port" element within the "service" section defines a specific endpoint for the service, and specifies the binding and address information for that endpoint. The "portType" section describes the operations that the service provides, while the "binding" section describes how those operations are bound to a specific communication protocol and message format. The "interface" section provides an abstract description of the operations and their parameters, and can be used to define multiple bindings for the same port type.

---------------------    
