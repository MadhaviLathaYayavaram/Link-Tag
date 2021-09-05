# Usage of Link Tag in HTML #

Link is tag used in Hypertext Markup Language which is famous for creating web pages with simple coding formats. Link Tag is used to connect external resources like style sheets, most importantly, CSS files which are used to design outputs on a web page. A relationship is created between the current HTML document so that the code in the external source is implemented as the native code. It may be specified in Cascade Style Sheets using "display" property. We can connect Style sheets whic h give a decoration to the structural elements of a webpage mentioned in the document. So it is very essential to load stylesheets in a webpage to make it more beautiful and understandable. Another powerful objective of link tag is that we can load favourite graphics as icons in the current website or mobile app and make it responsive. 

Link tag is used in the 'head' section of HTML code. As the Link tag is empty element, it does not have an end tag, but may contain attraibutes to set its features. It supports many numbers of Global attributes, and Event attributes that can be set for different functionalities. Link tag is supported by all the advanced browsers like Chrome, Edge, Firefox, Safari, and Opera.  It is given in the syntax <link attribute1='value', attribute2='value',...>

## StyleSheets ##

Stylesheets are coded using CSS design and can be linked in a HTML document to import all the styles into the current elements like headers, paras, input, text, passwords etcetera. Anyways, the inline syles of the front-end document overwrite the styles specified in the linked stylesheets, as they do have higher priority. Event handlers can be declared for the link tag. 


## Link Attributes ##

Rel : It is a very important and compulsory attribute in Link tag to establish a relationship between the linked document ant the current HTML. For example, if we want to connect a CSS style sheet to the current document, we need to insert the attribute 'Rel="stylesheet' in the link tag.  

Href : This attribute provides the physical path to relate the style sheet. The css files can be linked through this attribute. We can also establish a relationship with different special icons  that can be loaded in the current document.

Hreflang :  This attribute allows to inform the type of language used in the linked document. The value is given in a two-letter code.  Ex: hreflang="en"

Media :  The media which is linked to the current document is specified here. The values could be Print, Screen, brailee, and Aural. Media queries will also be identified in advanced versions of browsers where this tag is used. 

Sizes: This allows to specify height and width of the display for the linked resources. It takes 'any' as default if not specified in the tag. For example, We can set  icons size  using "sizes" attribute. ex: sizes="114x114"

Type: It denotes the media file type (MIME) and tells the format of it to the browser. We can make conditions to follow the media in the same attribute which will be executed only when the condition satisfies. Ex: media="screen and (max-width: 600px)",   Ex: media="print",  Ex: type="image/png".

Title : It is used to specify one or an alternative style sheet to be applied in the current document. 



There are so many non-standard attribute that can be used in the link tag. The main objective of the tag is to innovate the front-end web pages using different source codes and make them responsive which are super advanced in their functionality!

