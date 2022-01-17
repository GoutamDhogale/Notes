<h2>ASP.NET Web API: Media-Type Formatters</h2>

* <p>Web API handles JSON and XML formats based on Accept and Content-Type headers. But, how does it handle these different formats? The answer is: By using Media-Type formatters.</p>
* <p>Media type formatters are classes responsible for serializing request/response data so that Web API can understand the request data format and send data in the format which client expects.</p>
* <p>A media type (also known as a Multipurpose Internet Mail Extensions or MIME type) indicates the nature and format of a document, file, or assortment of bytes.</p>

<br>
<table class="table table-bordered">
            <thead>
                <tr>
                    <th>Media Type Formatter Class
                    </th>
                    <th>MIME Type
                    </th>
                    <th>Description
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>JsonMediaTypeFormatter  
                    </td>
                    <td>application/json, text/json
                    </td>
                    <td>Handles JSON format
                    </td>
                </tr>
                <tr>
                    <td>XmlMediaTypeFormatter  
                    </td>
                    <td>application/xml, text/json
                    </td>
                    <td>Handles XML format
                    </td>
                </tr>
                <tr>
                    <td>FormUrlEncodedMediaTypeFormatter  
                    </td>
                    <td>application/x-www-form-urlencoded
                    </td>
                    <td>Handles HTML form URL-encoded data
                    </td>
                </tr>
                <tr>
                    <td>JQueryMvcFormUrlEncodedFormatter  
                    </td>
                    <td>application/x-www-form-urlencoded
                    </td>
                    <td>Handles model-bound HTML form URL-encoded data
                    </td>
                </tr>
            </tbody>
        </table>
        <br>
        
   <a href="https://www.tutorialsteacher.com/webapi/web-api-formatters">Formatters</a>     
 
