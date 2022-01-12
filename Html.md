# Notes
Html notes
--------------

 *  html-hypertext markup language .It was used to develoup the web pages. using this we can easily develoup browser readable pages.
 * invented by Tim Berners-Lee invented @1989
 * HTML is the standard markup language for Web pages.
 
Main Tags 
---------------
* The  &lt;!DOCTYPE html&gt; declaration defines that this document is an HTML5 document
* The &lt;html&gt; element is the root element of an HTML page
* The &lt;head&gt;element contains meta information about the HTML page
* The &lt;title&gt; element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
* The &lt;body&gt; element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
* The &lt;h1&gt; element defines a large heading
* The &lt;p&gt; element defines a paragraph
  
Element:
==============  
 * &lt;h1&gt;My First Heading&lt/h1&gt; full thing from start to end 
  
Use of browser in Html
=====================
* The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

 Html structure
 =================
  <pre> 
&lt;div class="html"&gt; 
    &lt;html&gt; 
    &lt;head&gt;&lt;title&gt;Title&lt;/title&gt;&lt;/head&gt; 
    &lt;body&gt; 
    &lt;p&gt;Unrendred html&lt;/p&gt; 
    &lt;/body&gt; 
    &lt;/html&gt; 
&lt;/div&gt; 
</pre> 
  ==================================================================
  
 * To create Html page you need notepad or textEditors
  
 The &lt;!DOCTYPE&gt; Declaration
 ---------------------------
* The &lt;!DOCTYPE&gt;declaration represents the document type, and helps browsers to display web pages correctly.

* It must only appear once, at the top of the page (before any HTML tags).

* The &lt;!DOCTYPE&gt; declaration is not case sensitive.
  
  * HTML headings are defined with the &lt;h1&gt; to &lt;h6&gt; tags: &lt;h1&gt;goutam&lt;/h1&gt;
  
  * HTML paragraphs are defined with the &lt;p&gt; tag: &lt;p&gt; meeting is on&lt;/p&gt;
  * HTML links are defined with the <-a> tag:
   &lt;a href="https://www.w3schools.com" &gt;This is a link&lt;/a&gt;
  * HTML images are defined with the &lt;img&gt; tag:
    The source file (src), alternative text (alt), width, and height are provided as attributes:
    Example
   &lt;img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142"&gt;
  * The &lt;br&gt; tag defines a line break
  
  Importent points
  -----------------
  * HTML elements can be nested (this means that elements can contain other elements)
  * Never skip the end tag
  * HTML tags are not case sensitive: &lt;P&gt; means the same as &lt;p&gt;
  
  ======================================================================
  
  HTML Attributes
  ----------------
  * HTML attributes provide additional information about HTML elements.
  * All HTML elements can have attributes
  * Attributes provide additional information about elements
  * Attributes are always specified in the start tag
  * Attributes usually come in name/value pairs like: name="value"
  * The &lt;a&gt; tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:
  * Double quotes around attribute values are the most common in HTML, but single quotes can also be used.
Example
  &lt;a href="https://www.w3schools.com" &gt;Visit W3Schools &lt;/a&gt;
  
  The &lt;img&gt; tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
Example
  &lt;img src="img_girl.jpg"&gt;
  
  URL Type:
  =========
  1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

     Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control           external images; it can suddenly be removed or changed.

  2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be  relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.
  
  
  =============================================================================
  
 The style Attribute:
 ---------------------
 
    * The style attribute is used to add styles to an element, such as color, font, size, and more.
  Example:
    &lt;p style="color:red;" &gt;This is a red paragraph.&lt;/p&gt;
  
==========================================================
  The lang Attribute:
  ---------------------
 
   *  You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.
       The following example specifies English as the language:
           
           <pre>
              &lt;!DOCTYPE html&gt;
              &lt; html lang="en" &gt;
                &lt; body &gt;
                        
                 &lt; /body &gt;
            &lt; /html &gt;
          </pre>
  
  The title Attribute
  ---------------------
  * The title attribute defines some extra information about an element.

  * The value of the title attribute will be displayed as a tooltip when you mouse over the element:

Example
  &lt;p title="I'm a tooltip"&gt;This is a paragraph.&lt;/p&gt;
  
  
  =========================================================================================================================================
  
  HTML Text Formatting
  --------------------
  * HTML contains several elements for defining text with a special meaning.
  *&ltbgt; - Bold text     -------------<b>This text is bold</b>    ---without any extra importance.
    &lt;strong&gt; - Important text------<strong>This text is important!</strong>      -----defines text with strong importance.
    &lt;i&gt;- Italic text-----<i>This text is italic</i>--------defines a part of text in an alternate voice or mood
    &lt;em&gt; - Emphasized text--- <em>This text is emphasized</em>------------verbal stress.
    &lt;mark&gt; - Marked text---------- highlighted
    &lt;small&gt; - Smaller text
    &lt;del&gt; - Deleted text
    &lt;ins&gt; - Inserted text---------------defines a text that has been inserted into a document. Browsers will usually underline inserted text:
    &lt;sub&gt; - Subscript text-----------Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:
    &lt;sup&gt; - Superscript text----------Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:
  ===============================================================================================
      

