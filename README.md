```python
What are API’s? How are they used and why are they so popular?

APIs are a standard set of protocols that enable applications to communicate with each
other and exchange information. They act as the gateway between applications,    
offering a set of defined rules which allow applications to ‘talk’ to each other and
share information.

APIs are used in various scenarios, including:
1. Integrating services: APIs enable different software systems to work together and share data.
2. Building applications: Developers use APIs to leverage existing functionalities and services provided by other applications or platforms.
3. Developing plugins or extensions: APIs allow developers to create plugins or extensions for existing applications or platforms.
4. Data access: APIs provide a structured way to access and retrieve data from databases or other systems. 

APIs are becoming critical to every facet of business. Popular applications of APIs include building new mobile applications, creating omnichannel experiences, improving e-commerce and development of more efficient business processes. They are so popular because they help in:
1. Accelerating digital transformation
2. Maintaining data integrity and data security
3. Improving the customer experience
4. Protecting security of proprietary data
5. Generating new sources of revenue 

```

```python
Add a diagram to showcase the data transfer process in API communication.


```
 ```python

What is a REST API? What makes an API RESTful?
A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services. REST stands for representational state transfer and was created by computer scientist Roy Fielding.
    
In order for an API to be considered RESTful, it has to conform to these criteria:

A client-server architecture made up of clients, servers, and resources, with requests managed through HTTP.
Stateless client-server communication, meaning no client information is stored between get requests and each request is separate and unconnected.
Cacheable data that streamlines client-server interactions.
A uniform interface between components so that information is transferred in a standard form. This requires that:
resources requested are identifiable and separate from the representations sent to the client.
resources can be manipulated by the client via the representation they receive because the representation contains enough information to do so.
self-descriptive messages returned to the client have enough information to describe how the client should process it.
hypertext/hypermedia is available, meaning that after accessing a resource the client should be able to use hyperlinks to find all other currently available actions they can take.
A layered system that organizes each type of server (those responsible for security, load-balancing, etc.) involved the retrieval of requested information into hierarchies, invisible to the client.
Code-on-demand (optional): the ability to send executable code from the server to the client when requested, extending client functionality. 
    
```
```python
What is HTTP? (what does it stand for and what is it used for? What is HTTPS?)

HTTP stands for Hypertext Transfer Protocol. It is a protocol that defines how data is transferred and communicated over the internet. HTTP enables communication between clients (such as web browsers) and servers (where web content is hosted) to facilitate the exchange of resources, such as HTML pages, images, videos, and more.

HTTPS (Hypertext Transfer Protocol Secure) is a secure version of HTTP. It adds an additional layer of security by using encryption to protect the data transmitted between the client and the server. HTTPS uses SSL/TLS (Secure Sockets Layer/Transport Layer Security) protocols to establish an encrypted connection. If you see https, the session between the web server and the browser on the mobile device you are using is encrypted
```
```python 

Explain HTTP request structure using the diagram provided.



```
```python
Explain HTTP response structure using the diagram provided.
```
 
```python
What are the 5 HTTP verbs and what do they do? GET, POST, PUT, PATCH, DELETE

HTTP verbs are: 

Retrieve a single/lists of item (GET)
Create an item (POST)
Updates/ Replaces an item (PUT)
Modifies/ Updates a resource. (PATCH)
Delete an item (DELETE)

```

What is statelessness?

 

What is caching?