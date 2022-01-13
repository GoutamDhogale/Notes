Angular
-------

* Angular is a frontEnd framework used to create SinglePageApplication.
* devaloupment language Typescript
* It helps to create scalable application by provoiding the component base platform.
<br>

Components
---------
* It is heart of the framework.it helps to create Independent pages and we can use it any where in the project.
* Reusable
* component contain @component Typescript class decorator,and also HTML templet and Css or styleing templet and testing (.spec) templets
* Selector is a unique key helps to connect with different component
* templete is a path where we  put html and css file paths to render ts file feture in html so that DOM can handel it.
* or we can directly mention the tags here if html page have one or two statements then its ok to directly mention that tags in .ts file (inside the templete)
* TempleteURL : responsible to handle HtML template
* StyleURL : responsible to handle css pages
 <br>
 
Example:
<br>

import { Component } from '@angular/core';

@Component({
<br>

  selector: 'hello-world',
  <br>
  
  template: `
  <br>
    &lt;h2&gt;Hello World&lt;/h2&gt;
    
  `
})
<br>

export class HelloWorldComponent {
  // The code in this class drives the component's behavior.
}

