## How does internet work?
Good question! Let me assure you that I have no intention to try to explain every aspect of how Internet is built up and configured. We will only focus on the parts that interests us as developers - and developers are not technicians. We don't deal with hardware and most of the 'how-does-it-work' discussions circle around hardware stuff. 

Forget about it.

## The HTTP-protocol

Let's have a closer look at stuff that matters for us as developers. And remember, we could go on forever and talk about this. But since we run a practical course and not a theoretical seminar - we will just scratch the surface of the HTTP protocol and the basics of how internet works.

**Hypertext Transfer Protocol (HTTP)** is the foundation of data communication on the internet - at least the part that concerns us at the moment, the World Wide Web. The main characteristic of HTTP is that it functions as a request-response protocol. 

### Request–Response
Request-Response is the most basic and common of the client-service interaction patterns. Accessing a web page is an example of request–response communication. First, a  computer (you via your browser) sends a request for some data (a web page) and then another computer (server) responds to the request. 

This pattern is typically implemented in a purely synchronous fashion, as in web service calls over HTTP, which holds a connection open and waits until the response is delivered or the timeout period expires. 

The HTTP protocol is **connection-** and **stateless**. The server and client are aware of each other only during a current request. Afterwards, both of them forget about each other. Due to this nature of the protocol, neither the client nor the browser can retain information between different requests across the web pages.

This is very important to understand when building applications that will run over HTTP protocol: the server forgets about who asked for what when a request have been served. 

### HTTP Verbs
The primary or most-commonly-used HTTP verbs are POST, GET, PUT, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. 

#### GET: Retrieve a resource

This is the main method used for retrieving html, images, JavaScript, CSS, etc. Most data that loads in your browser was requested using this method.

#### POST: Send Data to the Server

Even though you can send data to the server using GET and the query string, in many cases POST will be preferable. Sending large amounts of data using GET is not practical and has limitations.

#### PUT & DELETE
**PUT** and **DELETE** are two other HTTP verbs. 
The PUT method requests that the enclosed entity be stored under the supplied URI. If the URI refers to an already existing resource, it is modified; if the URI does not point to an existing resource, then the server can create the resource with that URI.

The DELETE method deletes the specified resource.

We will return to these methods further down the road when a more detailed discussion of the main HTTP verbs is required.

### HTTP Status Codes
* 200's are used for successful requests.
* 300's are for redirections.
* 400's are used if there was a problem with the request.
* 500's are used if there was a problem with the server.

**Let's give it a rest for now. No need to get a headache over this. We're here to code, right?**
