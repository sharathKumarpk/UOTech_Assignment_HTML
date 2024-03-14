## Q.1 What is the use of `<!DOCTYPE html>`?
## A. The `<!DOCTYPE html> `declaration is an essential part of an HTML document, and it stands for Document Type Definition
## .It is used to define the document type and version of HTML that a web page is written in. Including this declaration at the beginning of an 
## HTML document helps the web browser understand how to interpret and render the content.

## Q.2 Explain Semantic tags in html? And why do we need it?
## A.
## Semantic tags in HTML are elements that carry meaning about the structure and content of a web page, making the HTML code more descriptive 
## and meaningful. Unlike non-semantic tags, which primarily define the appearance of the content, semantic tags provide information about the 
## purpose and role of the content they enclose. Using semantic tags is beneficial for both developers and browsers because they enhance the 
## clarity, accessibility, and search engine optimization (SEO) of web pages.

## Here are some commonly used semantic tags in HTML5:
## 1.`<header>`
## 2.`<article>`
## 3.`<footer>`
##  Using semantic tags has several advantages:
## 1.Improved Accessibility
## 2.Search Engine Optimization (SEO)
## 3.Code Readability
## 4.Consistency

## Q.3 Differentiate between HTML Tags and Elements?
## A.
## HTML TAGS:
## 1.Tags are the fundamental building blocks of HTML.
## 2.They are used to define and markup the structure of the content within an HTML document.
## 3.Tags are enclosed in angle brackets (< and >).
## 4.Tags are often used in pairs – an opening tag and a closing tag.
## HTML ELEMENTS:
## 1.An element is a complete set of tags and the content they enclose.
## 2.It consists of the opening tag, the content, and the closing tag (in the case of elements that have content).
## 3.Elements can also be self-closing, in which case there is only one tag (self-closing tag).
            
## Q.4 What are some of the advantages of HTML5 over its previous versions?
## A.
## HTML5 introduced several new features and improvements over its predecessor, HTML4, and other previous versions of the language. Some of the key advantages of HTML5 include:

## 1.Semantic Elements
## 2.Audio and Video Support
## 3.Canvas Element
## 4.Improved Forms
## 5.Local Storage
## 6.Geolocation API
## 7.WebSockets
## 8.Responsive Design Support
## 9.Improved Accessibility
## 10.Compatibility and Consistency

# Q.5 What is the difference between <figure> tag and<img>tag?
# A.
## The `<figure> `and `<img>` tags are both HTML elements, but they serve different purposes in structuring and presenting content on a web page.

## `<img>`TAGS:
##  1.The `<img> `(image) tag is used to embed images in an HTML document.
##  2.It is a self-closing tag and does not have a closing tag.
##  3.It is used to display a standalone image on a page.
## 4.The `<img>` tag typically includes attributes such as src (source) to specify the image file, alt for alternative text, and optional attributes like width and height to define the dimensions.

## `<figure>` and `<figcaption>` TAGS:
## 1.The `<figure>` tag is used to group together content that is referenced as a single unit, such as an image, a video, a diagram, or code.
## 2.The `<figcaption>` tag, when used inside a `<figure>` element, provides a caption or description for the content within the <figure>.
## 3.The combination of `<figure>` and `<figcaption>` is often used to associate a caption with an image or other content.

## Q.6 What is the difference between `<link>`tag and `<a`>`tag?
## A.
## The `<link>` and `<a>` tags serve different purposes in HTML and are used in distinct contexts:

## `<link>`TAGS:
## 1.The `<link>` tag is used to define external resources or relationships between the current document and an external resource.
## 2.It is commonly used in the <head> section of an HTML document to link to external stylesheets, icon files, or other resources.
## 3.The most common use is to link an external stylesheet to apply styles to the HTML document.
## `<head>`
##  `<link rel="stylesheet" type="text/css" href="styles.css">`
## `</head>`
##  The "rel" attribute specifies the relationship between the current document and the linked resource.

## `<a>`TAGS:
## 1.The `<a>` (anchor) tag is used to create hyperlinks, allowing users to navigate to other pages or resources.
## 2.It is often used in the body of the HTML document to create clickable links.
## 3.The href attribute in the `<a>` tag specifies the destination URL or the target resource.

## Q.7 What forms in HTML?
## A. A webform, web form or HTML form on a web page allows a user to enter data that is sent to a server for processing. Forms can resemble paper or database forms because web users fill out the forms using checkboxes, radio buttons, or text fields.

## Q.8 What are Semantic elements?
## A. Semantic HTML elements are those that clearly describe their meaning in a human- and machine-readable way. Elements such as `<header>` , `<footer>` and `<article> `are all considered semantic because they accurately describe the purpose of the element and the type of content that is inside them.

## Q.9 What are empty elements?
## A. An empty element is a component that doesn't have any embedded elements or text elements. Empty tags contain only the opening tag but they perform some action in the webpage. For example, <br> tag is an empty tag.

## Q.10 What's the difference between html tag and attribute and give example of some golbal attributes?
## A. In HTML, both tags and attributes play crucial roles in defining the structure and presentation of content on a web page.
   
## HTML TAGS:
## 1.A tag is a fundamental building block of HTML and is used to define and structure different parts of the content.
## 2.Tags are enclosed in angle brackets (< and >).
## 3.Tags are typically used in pairs—an opening tag and a closing tag—to enclose content.
## `<p>`This is a paragraph.`</p>`
## In the example above, `<p>` is the opening tag, and` </p> `is the closing tag. The content ("This is a paragraph.") is enclosed between these tags.

## HTML Attribute: 
## 1.An attribute provides additional information about an HTML element and is always included within the opening tag.
## 2.Attributes are added to the opening tag and are written as name/value pairs.
## 3.Attributes provide extra details or properties for an element.
## `<img src="example.jpg" alt="An example image">`
## In the example above, src and alt are attributes of the <img> tag. They provide information about the image source and alternative text, respectively.
   
## Global Attributes:
## Global attributes are attributes that can be used on any HTML element, regardless of its type. Some common global attributes include:
    
## 1.class:
## *Specifies one or more class names for an element, which can be used to style and target the element with CSS.
## `<div class="container">`This is a container.`</div>`

## 2.id:
## *Provides a unique identifier for an element, which can be used for styling or scripting purposes. It should be unique within the document.
## `<h1 id="pageTitle">Page Title</h1>`

## 3.style:
## *Allows inline CSS styling for an element.
##` <p style="color: blue; font-size: 16px;">This is a styled paragraph.</p>`

## 4.title:
## *Adds advisory information or a tooltip for an element. When the user hovers over the element, the title text is displayed.
## `<a href="https://www.example.com" title="Visit Example.com">Link</a>`

## 5.lang:
## *Specifies the language of the content within the element.
##` <html lang="en">`
## `<!-- Document content goes here -->`
## `</html>`


