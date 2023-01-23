# Class 1 Notes

>> How the Web Works 

1.-Through the HTTP protocol, resources are exchanged between client devices and servers over the internet. Client devices send requests to servers for the resources      needed to load a web page; the servers send responses back to the client to fulfill the requests.

2.-The browser parses HTML into a DOM tree. HTML parsing involves tokenization and tree construction. HTML tokens include start and end tags, as well as attribute        names and values. If the document is well-formed, parsing it is straightforward and faster.

   -The CSS parser takes the bytes and converts them into characters, then tokens, then nodes and finally they are linked into the CSSOM. The browser does something      called selector machting which means that each set of styles will be matched against all nodes (elements) on the page

   -JavaScript is interpreted, compiled, parsed and executed. The scripts are parsed into abstract syntax trees. Some browser engines take the Abstract Syntax Tree and    pass it into an interpreter, outputting bytecode which is executed on the main thread. This is known as JavaScript compilation.

3.-Unsplash. Unsplash — Free image search. ...
   Burst (by Shopify) Burst – Free image search
   Pexels. Pexels – free image search
   Pixabay. Pixabay – free stock photos
   Free Images. Free images – stock photos
   Kaboompics. Kaboompics – photo search by color
   Stocksnap.io. Stocksnap free photos

4.-A JavaScript variable is simply a name of storage location. There are two types of variables in JavaScript : local variable and global variable. There are some        rules while declaring a JavaScript variable (also known as identifiers). Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.

>> Introduction to HTML 

1.-An HTML attribute is a piece of markup language used to adjust the behavior or display of an HTML element. For example, attributes can be used to change the color,    size, or functionality of HTML elements.

2.-HTML is made up of a series of hierarchical elements. Most elements have an opening tag and a closing tag, with content sandwiched in between.
   <! DOCTYPE>   <html >  <head >  <title >  <body >
  
3.- <article> Tag: This tag contains independent content that doesn’t require any other context. So the <article> tag can be placed inside the main content. But each      of the articles will contain independent content within it.

   <section> Tag: This tag is used to split a page into sections like Introduction, Contact Information, Details, etc and each of these sections can be in a different    <section> tag. The <section> tag is introduced to wrap-up the things in a particular section. The <section> tag divides the content into sections and subsections.      The section tag is used when requirements of two headers or footers or any other section of documents needed. Section tag grouped the generic block of related          content.
 
4.- 01. Header & menu  02. Images  03. Website content  04. Footer
     
5.-Metadata helps to describe the information on your webpage in a way Google or other search engines can better understand. That includes your landing pages, as well   as your blogs, articles, and eBooks. There are two main forms of metadata, including: Descriptive metadata: Basic information about a piece of data.
  
6.-The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data. <meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
     
     
>> How to start to design a Website 
  
1.- Identify your goal
     
2.- Who is the website for? 
    One of the most important steps is identifying your ideal audience and anticipated visitors by demographic data, tech-savviness, intent, personal goals and pain       point, the stage of their purchase decision making, and more.
  
>> Semantics 
     
1.- By default, most browser's user agent stylesheet will style an <h1 > with a large font size to make it look like a heading.
   Using <span > will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is            therefore a good idea to use the right HTML element for the right job.
     
2.-The semantic HTML tags help the search engines and other user devices to determine the importance and context of web pages.
   The pages made with semantic elements are much easier to read.
   It has greater accessibility. It offers a better user experience.
     
>> What is JavaScript? 
     
1.--Show or hide more information with the click of a button  
   -Change the color of a button when the mouse hovers over it  
   -Slide through a carousel of images on the homepage
   -Zooming in or zooming out on an image
   -Displaying a timer or count-down on a website
   -Playing audio and video in a web page
   -Displaying animations
   -Using a drop-down hamburger menu

2.-You can add JavaScript code in an HTML document by employing the dedicated HTML tag <script> that wraps around JavaScript code. The <script> tag can be placed in      the <head> section of your HTML or in the <body> section
     
     
     
  
## Things I want to know more about
