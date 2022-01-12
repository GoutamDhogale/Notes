# Notes
Html notes
--------------
 *html-hypertext markup language .It was used to develoup the web pages. using this we can easily develoup browser readable pages.
 * invented by Tim Berners-Lee invented @1989
*HTML is the standard markup language for Web pages.
Main Tags 
---------------
*The <!DOCTYPE html> declaration defines that this document is an HTML5 document
*The <html> element is the root element of an HTML page
*The <head> element contains meta information about the HTML page
*The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
*The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
*The <h1> element defines a large heading
*The <p> element defines a paragraph
  
Element:
==============  
  <h1>My First Heading</h1>  full thing from start to end 
  
 Use of browser in Html
 =====================
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

  Html structure
  =================
  <html>                              ------html root element every element start with html tag
    <head>                            ------head is the container contain all meta details about the webpage
      
      <meta element>
      </meta element>
    </head>                            -------/ represent tag scope end here
  <body>                              --------body tag is contain the whole detail doc or content of the page
    //statements
  </body>
  </html>
  ==================================================================
  
 * To create Html page you need notepad or textEditors
  
  The <!DOCTYPE> Declaration
  ---------------------------
*The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

*It must only appear once, at the top of the page (before any HTML tags).

*The <!DOCTYPE> declaration is not case sensitive.
  
  *HTML headings are defined with the <h1> to <h6> tags: <h1>goutam</h1>
  *HTML paragraphs are defined with the <p> tag: <p> meeting is on</p>
  *HTML links are defined with the <a> tag: <a href="https://www.w3schools.com">This is a link</a>
  *HTML images are defined with the <img> tag:
    The source file (src), alternative text (alt), width, and height are provided as attributes:
    Example
   <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
  *The <br> tag defines a line break
  
  Importent points
  -----------------
  *HTML elements can be nested (this means that elements can contain other elements)
  *Never skip the end tag
  *HTML tags are not case sensitive: <P> means the same as <p>.
  
  ======================================================================
  HTML Attributes
  ----------------
  * HTML attributes provide additional information about HTML elements.
  * All HTML elements can have attributes
  * Attributes provide additional information about elements
  * Attributes are always specified in the start tag
  * Attributes usually come in name/value pairs like: name="value"
  * The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:
  * Double quotes around attribute values are the most common in HTML, but single quotes can also be used.
Example
  <a href="https://www.w3schools.com">Visit W3Schools</a>
  
  The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
Example
  <img src="img_girl.jpg">
  
  URL Type:
  =========
  1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

     Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control           external images; it can suddenly be removed or changed.

  2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be  relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.
  
  
  =================================================================================================================================================================
  The style Attribute
  -------------------
    The style attribute is used to add styles to an element, such as color, font, size, and more.

   Example
      <p style="color:red;">This is a red paragraph.</p>
  

  The lang Attribute
  -------------------
    You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

    The following example specifies English as the language:

            <!DOCTYPE html>
            <html lang="en">
                <body>
                        ...
                 </body>
            </html>
  
  The title Attribute
  ---------------------
  * The title attribute defines some extra information about an element.

  * The value of the title attribute will be displayed as a tooltip when you mouse over the element:

Example
  <p title="I'm a tooltip">This is a paragraph.</p>
  
  
  =========================================================================================================================================
  
  HTML Text Formatting
  --------------------
  * HTML contains several elements for defining text with a special meaning.
  * <b> - Bold text     -------------<b>This text is bold</b>    ---without any extra importance.
    <strong> - Important text------<strong>This text is important!</strong>      -----defines text with strong importance.
    <i> - Italic text-----<i>This text is italic</i>--------defines a part of text in an alternate voice or mood
    <em> - Emphasized text--- <em>This text is emphasized</em>------------verbal stress.
    <mark> - Marked text---------- highlighted
    <small> - Smaller text
    <del> - Deleted text
    <ins> - Inserted text---------------defines a text that has been inserted into a document. Browsers will usually underline inserted text:
    <sub> - Subscript text-----------Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:
    <sup> - Superscript text----------Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:
  ===============================================================================================
      
      
      
