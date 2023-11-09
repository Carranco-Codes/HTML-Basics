# HTML Basics | Essentials and Document Structure
PDF Download - [HTML Basics - Essentials and document structure.pdf](https://github.com/Carranco-Codes/HTML-Basics/files/13313622/HTML.Basics.-.Essentials.and.document.structure.pdf)

## What is HTML and where is it used?
HTML, or HyperText Markup Language, is at the core of every website. Whether you are looking at a website for a small business or an application for a large enterprise, if it’s on the internet, it contains HTML. HTML primarily focuses on the visual components of a website creating the user interface we interact with. It defines the structure and layout of web pages, including headings, paragraphs, images, links, and forms. But HTML is not just limited to websites. It is also used in email templates, online documentation, and other digital content.

## Frontend vs Backend
The front end contains all the visual components of a website. Anything and everything you see on a website is “front-end development.” 

The backend is stuff that feeds the website that a user will never see. This could be data being called, such as a list of portfolio information, or data being sent, such as form data being submitted from a website.

## Displaying HTML
HTML files end with the extension “.html”. Typically, when you name a file “index.html,” you tell the server that this file is what you want to spin up as your home page. This could be adjusted in some settings, but in this series we will be using the default settings. By assigning a page to the “homepage” you can access the file by going straight to the “domain”. In the video we spin up a server using the Live Server extension. 127.0.0.1 is the domain that gets served by Live Server. 127.0.0.1 is also well known as your local server. You can access your homepage by going directly to 127.0.0.1:5500 or by adding the file name. 127.0.0.1:5500/index.html
![URL demo](https://github.com/Carranco-Codes/HTML-Basics/assets/10298176/22fd4fa7-03c9-4a7c-8356-e4654f076695)

## HTML Elements
HTML elements contain three different parts: Opening Tag, Closing Tag, and Content. An element is everything from the opening tag to then end of the closing tag.
![element-diagram](https://github.com/Carranco-Codes/HTML-Basics/assets/10298176/48bbc3de-ff0f-4078-b117-b0b713826d05)

#### Sample h1 element
```
<h1>Sample Element</h1>
```
#### Sample section element
```
<section>
    <h1>Sample Element</h1>
</section>
```

#### Sample image element
```
<img src='img.jpg' />
```

### Opening Tags
The opening tag is the initial tag. Notice that in the “Sample h1 element” example, the opening tag has no slash. `<h1>` is the opening tag.

### Closing Tags
The closing tag is the ending tag. Notice that in the “Sample h1 element” example, the closing tag has a forward slash. `</h1>` is the closing tag.

### Self-Closing Tags
A self-closing tag is a tag that has no content and therefore cannot have any children. The most common self-closing tag is an img element. In the “Sample image element“. Notice that the forward slash is at the end of the element. `<img src='img.jpg' />`

## Attributes
Attributes provide more information about the element and are always placed in the opening tag. In the “Sample image element“. The src=‘img.jpg’ is an attribute to the img element. In that example “src” is the attribute type and “img.jpg” is the value. <img src=‘img.jpg’ />

## Four required parts to any HTML document

### Doctype
All HTML must start with a `<!DOCTYPE>` declaration. Doctype is not an HTML tag but provides information to the browser on what kind of file to expect. Doctype is not case-sensitive, but it is common to see it in all uppercase or all lowercase.

### html element
Below the doctype, you start an HTML document with the `<html>` element. This wraps all the components of an html document. The HTML element takes a language tag that is lang. To use that we will want to add the `lang` name with the value “en”. Inside that element, you’ll need the `<head>` element and `<body>` element.

### head element
The head contains all the metadata that is sent to the browser. Everything in the head is not visible to the user but information that browsers.
### body element
The body element contains all the contents of an HTML document that are visible to a user. Examples of these contents are sections, paragraphs, images, links, tables, lists, etc.

```
<!doctype html>
<html lang="en">
	<head></head>
	<body></body>
</html>
```

# Terms
| Term          	| Definition                                                                                                                              	  							|
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Front-end     	| The front end contains all the visual components of a website. Anything and everything you see on a website is "front-end development." 								|
| Back-end      	| Back-end development means working on server-side software, which focuses on everything you can't see on a website.					  								|
| homepage      	| The main web page of a website. This can be accessed by directly going to the domain or going to the index.html file 					  								|
| 127.0.0.1     	| Most common URL for a local server 																									  								|
| domain        	| A domain name is a friendly name that replaces the IP address in the url. For instance `localhost` can replace 127.0.0.1		       	  								|
| Port Number   	| A way to identify a specific process to which an internet or other network message is to be forwarded when it arrives at a server.      								|
| Element       	| HTML elements contain three different parts: Opening Tag, Closing Tag, and Content. An element is everything from the opening tag to then end of the closing tag.     |
| Opening Tag   	| The opening tag is the initial tag, the opening tag has no slash. `<h1>` is an example of an opening tag.			                      								|
| Closing Tag   	| The closing tag is the ending tag, the closing tag has a forward slash. </h1> is an example of a closing tag.                           								|
| Self-closing tag 	| A self-closing tag has no content and therefore cannot have any children. Notice that the forward slash is at the end of the element. `<img src='img.jpg' />`         |
| Attribute     	| Attributes provide more information about the element and are always placed in the opening tag. 												                        |
| Nesting       	| Placing one element inside another element.																								                            |
| <!doctype>    	| A declation that sends "information" to the browser about what document type to expect.                                  												|
| <html></html> 	| This wraps all the components of an html document. Inside that element, you’ll need the `<head>` element and `<body>` element.   		                                |
| <head></head> 	| The head contains all the metadata that is sent to the browser                                    																	|
| <body></body> 	| The body element contains all the contents of an HTML document that are visible to a user.										                                    |
