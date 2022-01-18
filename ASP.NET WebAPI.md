<h2><i>ASP.NET WebAPI</i></h2>

![image](https://user-images.githubusercontent.com/97591175/149748913-92c2257f-41b2-46a4-9880-81052e1e587e.png)


<p>ASP.NET Web API is a framework for building HTTP services that can be accessed from any client including browsers and mobile devices. It is an ideal platform for building RESTful applications on the .NET Framework.</p>


<h2><i>What is Web API?
</i></h2>

* <p> API is some kind of interface which has a set of functions that allow programmers to access specific features or data of an application, operating system or other services.</p>
* <p>Web API as the name suggests, is an API over the web which can be accessed using HTTP protocol. It is a concept and not a technology. We can build Web API using different technologies such as Java, .NET etc. For example, Twitter's REST APIs provide programmatic access to read and write data using which we can integrate twitter's capabilities into our own application</p>
* <p>It works more or less the same way as ASP.NET MVC web application except that it sends data as a response instead of html view. It is like a webservice or WCF service but the exception is that it only supports HTTP protocol.</p>

  <h2><i>ASP.NET Web API Characteristics</i></h2>
  
<ul>
<li>ASP.NET Web API is an ideal platform for building RESTful services.</li>
  <li>ASP.NET Web API is built on top of ASP.NET and supports ASP.NET request/response pipeline</li>
  <li>ASP.NET Web API maps HTTP verbs to method names.</li>
  <li>ASP.NET Web API supports different formats of response data. Built-in support for JSON, XML, BSON format.</li>
  <li>ASP.NET Web API can be hosted in IIS, Self-hosted or other web server that supports .NET 4.0+.</li>
  <li>ASP.NET Web API framework includes new HttpClient to communicate with Web API server. HttpClient can be used in ASP.MVC server side, Windows Form application, Console application or other apps.</li>
 

</ul>
</p>

<table class="table table-bordered">
            <thead>
                <tr>
                    <th class="w-50">Web API
                    </th>
                    <th class="w-50">WCF
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Open source and ships with .NET framework.
                    </td>
                    <td>Ships with .NET framework
                    </td>
                </tr>
                <tr>
                    <td>Supports only HTTP protocol.
                    </td>
                    <td>Supports HTTP, TCP, UDP and custom transport protocol.
                    </td>
                </tr>
                <tr>
                    <td>Maps http verbs to methods
                    </td>
                    <td>Uses attributes based programming model.
                    </td>
                </tr>
                <tr>
                    <td>Uses routing and controller concept similar to ASP.NET MVC.
                    </td>
                    <td>Uses Service, Operation and Data contracts.
                    </td>
                </tr>
                <tr>
                    <td>Does not support Reliable Messaging and transaction.
                    </td>
                    <td>Supports Reliable Messaging and Transactions.
                    </td>
                </tr>
                <tr>
                    <td>Web API can be configured using HttpConfiguration class but not in web.config.
                    </td>
                    <td>Uses web.config and attributes to configure a service.
                    </td>
                </tr>
                <tr>
                    <td>Ideal for building RESTful services.
                    </td>
                    <td>Supports RESTful services but with limitations.
                    </td>
                </tr>
            </tbody>
        </table>
<p></p>

<h2><i>Web API Controllers</i></h2>

<p>It handles incoming HTTP requests and send response back to the caller.</p>
<p>Web API controller is a class which can be created under the Controllers folder or any other folder under your project's root folder. The name of a controller class must end with "Controller" and it must be derived from System.Web.Http.ApiController class. All the public methods of the controller are called action methods.</p>

![image](https://user-images.githubusercontent.com/97591175/149757529-02cf9ea4-d56d-415c-816a-7db3e53f69df.png)


<p><b>IMPORTENT:<b>If you want to write methods that do not start with an HTTP verb then you can apply the appropriate http verb attribute on the method such as HttpGet, HttpPost, HttpPut etc. same as MVC controller.</p>
        [HttpGet]
        <br>
        public IEnumerable<string> Values()
        <br>
        {
        <br>
            return new string[] { "value1", "value2" };
        <br>
        }</b>
        <br>

        




  
  
  
  
  <table class="table table-bordered">
            <thead>
                <tr>
                    <th class="w-50">
                        Web API Controller
                    </th>
                    <th class="w-50">
                        MVC Controller
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Derives from System.Web.Http.ApiController class
                    </td>
                    <td>Derives from System.Web.Mvc.Controller class.
                    </td>
                </tr>
                <tr>
                    <td>Method name must start with Http verbs otherwise apply http verbs attribute. 
                    </td>
                    <td>Must apply appropriate Http verbs attribute.
                    </td>
                </tr>
                <tr>
                    <td>Specialized in returning data.
                    </td>
                    <td>Specialized in rendering view.
                    </td>
                </tr>
                <tr>
                    <td>Return data automatically formatted based on Accept-Type header attribute. Default to json or xml.
                    </td>
                    <td>Returns ActionResult or any derived type.
                    </td>
                </tr>
                <tr>
                    <td>Requires .NET 4.0 or above
                    </td>
                    <td>Requires .NET 3.5 or above
                    </td>
                </tr>
            </tbody>
        </table>
  
  ![image](https://user-images.githubusercontent.com/97591175/149765911-a100967e-7e44-4313-97b3-f161ec063886.png)

<p></p>
  <h2>Web.config properties</h2>
  
  <table class="table table-bordered">
            <thead>
                <tr>
                    <th>
                        Property
                    </th>
                    <th>
                        Description
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>DependencyResolver
                    </td>
                    <td>Gets or sets the dependency resolver for dependency injection.
                    </td>
                </tr>
                <tr>
                    <td>Filters
                    </td>
                    <td>Gets or sets the filters.
                    </td>
                </tr>
                <tr>
                    <td>Formatters
                    </td>
                    <td>Gets or sets the media-type formatters.
                    </td>
                </tr>
                <tr>
                    <td>IncludeErrorDetailPolicy
                    </td>
                    <td>Gets or sets a value indicating whether error details should be included in error messages.
                    </td>
                </tr>
                <tr>
                    <td>MessageHandlers
                    </td>
                    <td>Gets or sets the message handlers.
                    </td>
                </tr>
                <tr>
                    <td>ParameterBindingRules
                    </td>
                    <td>Gets the collection of rules for how parameters should be bound.
                    </td>
                </tr>
                <tr>
                    <td>Properties
                    </td>
                    <td>Gets the properties associated with this Web API instance.
                    </td>
                </tr>
                <tr>
                    <td>Routes
                    </td>
                    <td>Gets the collection of routes configured for the Web API.
                    </td>
                </tr>
                <tr>
                    <td>Services
                    </td>
                    <td>Gets the Web API services.
                    </td>
                </tr>
            </tbody>
        </table>
  
  
  <h2>Web API Routing</h2>
  
  <p>Web API routing is similar to ASP.NET MVC Routing. It routes an incoming HTTP request to a particular action method on a Web API controller.</p>
  
  <p>Web API supports two types of routing:
  <ul>
    <li>Conventional Based Routing</li>
    <li>Attribute</li>
  </ul>
  
  </p>
  
  <h2><i>Parameter Binding in ASP.NET Web API</i></h2>
  <p>It will helps to route the client side Http request to the Action method of the controller.It will map request to the action method.</p>
  <p>Action Method of controller have one or more parameter like 
<ul>
  <li>Primitive </li>
  <li>complex</li>

</ul>
</p>
  
  <p> Web API binds action method parameters with the URL's query string or with the request body depending on the parameter type.</p>
  
  <p>By default, if the parameter type is of .NET primitive types such as int, bool, double, string, GUID, DateTime, decimal, or any other type that can be converted from string type, then it sets the value of a parameter from the query string. And if the parameter type is the complex type, then Web API tries to get the value from the request body by default.</p>
  
  <p></p>
  
  <p></p>
  
  
  
  
