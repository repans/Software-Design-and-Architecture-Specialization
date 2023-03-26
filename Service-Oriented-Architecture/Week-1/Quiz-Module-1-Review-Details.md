# Module 1 Review Details 

### Question: You are probably using the internet to do some of your personal banking. There is a page that shows your accounts and their balances, often called something like "Account Summary" or "Account Overview." You must click on an account to begin managing it. Which type of web page is this?
  
a. web service    
b. web app  
c. **dynamic web page**  
d. static web page   

This is a **dynamic web page**.

A dynamic web page is a web page that displays different content each time it is viewed. The content of a dynamic web page is generated on the server-side and can change based on various factors, such as user input, database queries, or other parameters. In this case, the web page is displaying the account summary and balances of the user's bank accounts, which can change frequently based on account activity, so it would be considered a dynamic web page.

A static web page, on the other hand, displays the same content each time it is viewed and does not change based on user input or other factors.

A web service is a software system that allows different applications to communicate with each other over the internet, typically using standardized protocols and interfaces.

A web app is a software application that runs in a web browser and is accessed over the internet. It can be either dynamic or static, depending on its functionality.

--------------   

### Question: Another web page allows interacting with a spreadsheet in a browser. You can enter in values, sum them up, perform operations on them, format them, etc. What type of web page is this? 
  
a. dynamic web page   
b. web service   
c. **web app**   
d. static web page   

This is a **web app**.

A web app is a software application that runs in a web browser and is accessed over the internet. It typically provides interactive functionality for users, allowing them to perform various tasks such as data entry, manipulation, and analysis. In this case, the web page allows users to interact with a spreadsheet in their browser, enter values, perform calculations, and format data, which would be considered interactive functionality and falls under the category of a web app.

A dynamic web page, as mentioned earlier, displays different content each time it is viewed based on various factors, such as user input, database queries, or other parameters.

A web service is a software system that allows different applications to communicate with each other over the internet, typically using standardized protocols and interfaces.

A static web page displays the same content each time it is viewed and does not change based on user input or other factors.

--------------   

### Question: Consider the two statements. Choose the one correct option. 

  1. JSON is a markup language
  2. JSON can easily be converted into a Javascript object

a. Neither statement is correct   
b. Both statements are correct   
c. Only the first statement is correct   
d. **Only the second statement is correct**   

The correct option is **Only the second statement is correct**.

JSON (JavaScript Object Notation) is not a markup language, but rather a lightweight data interchange format that is easy for humans to read and write, and easy for machines to parse and generate. JSON is often used to transmit data between a server and a web application, as an alternative to XML.

JSON can easily be converted into a JavaScript object, and vice versa, as it is a subset of the JavaScript programming language. This makes it easy to use JSON data in JavaScript applications.

--------------   

### Question: Which of these is NOT a basic standard of the World Wide Web?

a. URL   
b. TCP   
c. HTTP   
d. **FTP**   

**FTP** (File Transfer Protocol) is not a basic standard of the World Wide Web.

URL (Uniform Resource Locator), TCP (Transmission Control Protocol), and HTTP (Hypertext Transfer Protocol) are all basic standards of the World Wide Web.

URL is a standardized way to specify the address of a web page or other resource on the internet. TCP is a fundamental protocol used to establish and manage connections between devices on the internet, while HTTP is a protocol used for transferring data over the internet, commonly used for retrieving web pages and other resources from web servers.

FTP, on the other hand, is a protocol used for transferring files over the internet, but it is not a basic standard of the World Wide Web. While FTP was used in the early days of the internet for transferring files, it has since been largely replaced by HTTP and other protocols for file transfers on the web.

--------------   

### Question: There is an HTTP method that allows you to send, create or update a resource, but allows the server to decide its location and identity. Which HTTP method is this?

a. SEND   
b. PUT   
c. GET   
d. **POST**  

The HTTP method that allows you to send, create, or update a resource, but allows the server to decide its location and identity is **POST**.

The POST method is used to submit an entity to the specified resource, often causing a change in state or side effects on the server. Unlike the PUT method, which requires the client to specify the URI of the resource being created or updated, the server decides the location and identity of the new resource created in response to the POST request.

The PUT method is used to update or create a resource at a specific URL, and the client must provide the full URL of the resource being updated or created.

The GET method is used to retrieve information about a resource from the server, while the SEND method is not a standard HTTP method.

--------------   

### Question: Which of these is often used to add dynamic content to a web page?

a. **Javascript**  
b. HTML   
c. HTML DOM   
d. CSS  

**JavaScript** is often used to add dynamic content to a web page.

JavaScript is a programming language that is commonly used to add interactivity and dynamic functionality to web pages. With JavaScript, developers can create dynamic effects such as animated menus, interactive maps, and real-time updates of data without the need to reload the entire page.

HTML is a markup language used to structure content on the web page, while CSS is used to style the content and layout of the page. While both HTML and CSS can affect the appearance of content on a web page, they do not provide the same level of interactivity and dynamic functionality as JavaScript.

HTML DOM (Document Object Model) is a programming interface for web documents that allows developers to manipulate the structure and content of a web page using JavaScript or other programming languages. While the HTML DOM can be used to add dynamic content to a web page, it is often done using JavaScript to make the web page more interactive and responsive.

--------------   

### Question: What are the three high-level components involved in a remote procedural call?

a. **client, server, interface definition language**   
b. marshal, client, server   
c. client stub, compiler, server stub     
d. IDL source code, IDL compiler, interface headers    

The three high-level components involved in a remote procedural call are:

a. **client, server, interface definition language**  

The three components in detail are:

Client: The client sends a request to the server for a particular operation to be performed.
Server: The server receives the request from the client and executes the requested operation.
Interface Definition Language (IDL): IDL is used to define the interface between the client and server, including the methods that can be called and the parameters that can be passed. IDL is used to generate client and server stubs that provide the necessary code to serialize and deserialize data and to handle network communication.
The other options are not correct:

b. Marshal, client, server - This is not a valid combination of components for a remote procedure call.

c. Client stub, compiler, server stub - This is a partial list of the components involved in generating client and server stubs for an RPC, but it does not include the IDL component.

d. IDL source code, IDL compiler, interface headers - This list includes the components involved in generating the IDL and client/server stubs, but it does not include the client and server components that are necessary for an RPC to occur.

--------------   

### Question: The process of establishing a connection between the client stub and server stub is called 

a. marshalling   
b. interfacing   
c. **binding**   
d. handshaking   

The process of establishing a connection between the client stub and server stub is called **binding**.

Binding refers to the process of connecting the client stub to the server stub, so that the client can send requests to the server and receive responses. During the binding process, the client and server stubs exchange information about how to communicate with each other, including the network address of the server and the protocol to be used for communication.

Marshalling refers to the process of converting the parameters of a remote procedure call into a format that can be transmitted over the network. Interfacing refers to the process of defining the interface between the client and server, including the methods that can be called and the parameters that can be passed. Handshaking refers to the process of establishing a connection between two devices over a network.

--------------   

### Question: What are the advantages of Common Object Request Broker Architecture (CORBA)? Choose the two correct answers. 

a. Dynamic binding is simple   
b. **Objects are essentially independent of their physical or virtual location**.  
c. **It allows for object-oriented paradigms in distributed computing**   
d. Method calls can be treated locally or remotely   

The advantages of Common Object Request Broker Architecture (CORBA) are:

b. **Objects are essentially independent of their physical or virtual location.**
c. **It allows for object-oriented paradigms in distributed computing.**

The advantages in detail are:

b. Objects are essentially independent of their physical or virtual location: CORBA enables objects to be distributed across multiple platforms and languages, allowing them to be used in distributed systems regardless of their location. This allows for greater flexibility and scalability in distributed systems.

c. It allows for object-oriented paradigms in distributed computing: CORBA is based on object-oriented programming (OOP) principles, making it easy to develop complex distributed systems that can be easily maintained and extended.

The other options are not correct:

a. Dynamic binding is simple: While CORBA does support dynamic binding, it is not necessarily simpler than other remote procedure call (RPC) frameworks.

d. Method calls can be treated locally or remotely: This is a feature of many RPC frameworks, including CORBA, but it is not a unique advantage of CORBA.

--------------   

### Question: Which of these are desirable characteristics of a web service? Select the three correct answers.  

a. **modular**    
b. simple   
c. **composable**   
d. **platform-independent**   

The desirable characteristics of a web service are:

a. **modular**   
c. **composable**    
d. **platform-independent**   

Explanation:   

a. Modular: A web service should be modular in design, with well-defined interfaces and functionality that can be easily extended or modified without affecting other components.

c. Composable: A web service should be designed to work well with other web services, allowing developers to combine multiple services to create complex applications.

d. Platform-independent: A web service should be platform-independent, meaning it can be used by any client regardless of the operating system or programming language they are using.

b. Simple: While simplicity can be desirable in some cases, it is not a universal characteristic of all web services. Some web services may require complex functionality to meet specific business requirements.

--------------   

### Question: Which of these responsibilities does the client stub have in a middleware-based architecture that uses RPC? Choose the three correct answers. 

a. Invoking the server application directly    
b. **Establishing a connection with the server**   
c. **Invoking the remote procedure call over the network**   
d. **Formatting and encoding data into standardized messages**   

The responsibilities of the client stub in a middleware-based architecture that uses RPC are:

b. **Establishing a connection with the server**   
c. **Invoking the remote procedure call over the network**   
d. **Formatting and encoding data into standardized messages**   

Explanation:

b. Establishing a connection with the server: The client stub is responsible for establishing a connection with the server, which involves finding the server on the network and establishing a network connection.

c. Invoking the remote procedure call over the network: The client stub is responsible for invoking the remote procedure call on the server, which involves marshalling the parameters of the call and sending them over the network to the server.

d. Formatting and encoding data into standardized messages: The client stub is responsible for formatting and encoding the data into standardized messages that can be transmitted over the network.

a. Invoking the server application directly: The client stub does not invoke the server application directly, as this would defeat the purpose of using middleware-based architecture. Instead, the client stub interacts with the middleware layer, which then forwards the request to the server.

--------------   

### Question: What is the main difference between a web service and a web application? 

a. **Web applications are presented through a browser**   
b. Web services are mostly meant for business applications  
c. Web services are simpler  
d. Web applications dynamically generate content  

The main difference between a web service and a web application is:   

a. **Web applications are presented through a browser**  

Explanation:

Web applications are presented through a web browser, while web services are not presented to end-users through a browser. Web services are designed to be consumed by other applications or services, while web applications are designed to be consumed directly by end-users through a browser. Web services provide a standardized way for applications to communicate with each other over the internet, whereas web applications are standalone applications that can be accessed through a web browser. Additionally, web services are typically used for machine-to-machine communication, while web applications are used for human-to-machine interaction.
