![image](https://user-images.githubusercontent.com/97591175/149613468-2c719865-dd5c-4367-aea3-ea47297ce28c.png)
![image](https://user-images.githubusercontent.com/97591175/149711532-d52d36b8-c206-4c15-b742-24e4c17e2bea.png)


<h2><i>REST VS SOAP</i></h2>

![image](https://user-images.githubusercontent.com/97591175/149613285-77bcb903-0a1c-410e-8167-bc65fa946420.png)

<h1><i>REST API</i></h1>

* <p>A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services.REST stands for representational state transfer and was created by computer scientist Roy Fielding.</p>
* <p>A RESTful API is an architectural style for an application program interface (API) that uses HTTP requests to access and use data. That data can be used to GET, PUT, POST and DELETE data types, which refers to the reading, updating, creating and deleting of operations concerning resources</p>
* <p>API allows two software programs to communicate with each other. </p>
* <p>A RESTful API -- also referred to as a RESTful web service or REST API -- is based on representational state transfer (REST), which is an architectural style and approach to communications often used in <b>web services development</b>.</p>
* <p><b>REST technology is generally preferred over other similar technologies</b>. This tends to be the case because REST uses less bandwidth, making it more suitable for efficient internet usage. RESTful APIs can also be built with programming languages such as JavaScript or Python.</p>
* <p>REST APIs allow users to connect to, manage and interact with cloud services flexibly in a distributed environment. RESTful APIs are used by such sites as Amazon, Google, LinkedIn and Twitter.</p>
* <h3><i>Example:</i></h3> <p>If i want some data about stock i will search on goolgle then click on search it will give some results regarding my search but if i think from where i am getting that data how it will featch thats the whole idea about <b>RESTAPI<br></b>If i send the request to server it will send responce in Json or in html or in xml</p>

<br>

![image](https://user-images.githubusercontent.com/97591175/149613392-4dbe7b76-90be-4850-b2b2-3d2da36e4701.png)


<h2><i>How RESTful APIs work</i></h2>
<p>A RESTful API breaks down a transaction to create a series of small modules. Each module addresses an underlying part of the transaction. This modularity provides developers with a lot of flexibility, but it can be challenging for developers to design their REST API from scratch. Currently, several companies provide models for developers to use; the models provided by Amazon S3, Cloud Data Management Interface (CDMI) and OpenStack Swift are the most popular.</p>

<p>A RESTful API uses commands to obtain resources. The state of a resource at any given timestamp is called a resource representation. A RESTful API uses existing HTTP methodologies defined by the RFC 2616 protocol, such as:</p>

* GET to retrieve a resource;
* PUT to change the state of or update a resource, which can be an object, file or block;
* POST to create that resource; and
* DELETE to remove it.
<p>With REST, networked components are a resource the user requests access to -- like a black box whose implementation details are unclear. All calls are stateless; nothing can be retained by the RESTful service between executions.</p>

<p>Data formats the REST API supports include:</p>

* <p>application/json</p>
* <p>application/xml</p>
* <p>application/x-wbe+xml</p>
* <p>application/x-www-form-urlencoded</p>
* <p>multipart/form-data</p>

<h2><i>Uses</i></h2>

<p>Because the calls are stateless, REST is useful in cloud applications. Stateless components can be freely redeployed if something fails, and they can scale to accommodate load changes. This is because any request can be directed to any instance of a component; there can be nothing saved that has to be remembered by the next transaction. That makes REST preferable for web use. The RESTful model is also helpful in cloud services because binding to a service through an API is a matter of controlling how the URL is decoded. Cloud computing and microservices are almost certain to make RESTful API design the rule in the future.</p>

<h2><i>RESTful API Design and Architecture Constraints</i></h2>
<p>Use of a uniform interface (UI). Resources should be uniquely identifiable through a single URL, and only by using the underlying methods of the network protocol, such as DELETE, PUT and GET with HTTP, should it be possible to manipulate a resource.</p>
<p>Client-server based. There should be a clear delineation between the client and server. UI and request-gathering concerns are the client's domain. Data access, workload management and security are the server's domain. This loose coupling of the client and server enables each to be developed and enhanced independent of the other.</p>

<p>Stateless operations. All client-server operations should be stateless, and any state management that is required should take place on the client, not the server.</p>
<p>RESTful resource caching. All resources should allow caching unless explicitly indicated that caching is not possible.</p>
<p>Layered system. REST allows for an architecture composed of multiple layers of servers.</p>
<p>Code on demand. Most of the time, a server will send back static representations of resources in the form of XML or JSON. However, when necessary, servers can send executable code to the client.</p>
<h2><i>API vs WebServices</i></h2>
<table>
  <tr>
    <th>API</th>
    <th>Webservice</th>
  </tr>
  <tr>
    <td>API is a software interface that allows two applications to interact with each other without any user involvement.</td>
    <td>Web service is a collection of open source protocols and standards used for exchanging data between systems or applications</td>
  </tr>
   <tr>
    <td>API is used for any style of communication.</td>
    <td>Web service is used for REST, SOAP and XML-RPC for communication</td>
  </tr>
   <tr>
    <td>API supports HTTP/HTTPS protocol</td>
    <td>Web service supports only HTTP protocol </td>
  </tr>
   <tr>
    <td>API supports XML and JSON.</td>
    <td>Web service supports XML</td>
  </tr>
   <tr>
    <td>APIs are not web services.</td>
    <td>All Web services are APIs</td>
  </tr>
  </table>

<h2><i></i></h2>

<h2><i></i></h2>


