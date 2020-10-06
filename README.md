# Frontend-Development-Workshop

##  Introduction to frontend development
What we typically see on a website is the user interface. This is the text, buttons, and images that helps us interact whats on the page.
Frontend development is the way to create these designs to use on a webpage. The term frontened development is usually used when creating a website, but it can be used when 
creating a mobile app or desktop application as well.

##  HTML
What is HTML? HTML stands for Hyper Text Markup Language and it is used to describe the structure of websites.

### Basic HTML Structure
To create an html file, you simply need to name your file with the .html file extension. At the beginning of your document, include the following line:

 ```<!DOCTYPE html>```
 
The building blocks of HTML are tags. Tags are used to structure a document and to contain elements on a page. 
To start, the root tag is is opened as <html> and closed as </html>. This tag is the root element of the HTML tree. All tags open with <tag> and close with </tag>. Here is an example of a very simple html file:

```
<!DOCTYPE html>

<html lang="en">
  <head>
    <title>Introduction to html</title>
  </head>
  
  <body>
    <h1>Welcome</h1>
    <p>Here we will teach you the basics of html tags so you can get started building webpages</p>
  </body>
</html>
```
In the first line, you can see that the DOCTYPE is declared as html. Below that, you can see the opening and closing html tag. Notice how everything else is contained within the <html> </html> part of the document. Whatever is contained within the <> and </> tags are called nested tags.

I will briefly list the other tags in this example as they are very important to any html file:

```<head>```: This element contains meta information about the document (title, externally linked files, metadata)<br />
```<title>```: Specifies the title of the page (shown in browser's title bar in each tab)<br />
```<body>```: This defines the html's body, this is where all elements seen on the page go<br />
```<h1>```: This is a large heading (there are headings of various sizes ```<h1>``` being the largest to ```<h6>``` being the smallest)<br />
```<p>```: This element defines a paragraph<br />

### Tags

There are a wide range of tags in html 

Inline vs block elements:

### Semantic HTML

The goal of HTML is to define a readable structure for your documents. With the new HTML5 specification, there were tags introduced to address some problems with the existing HTML tags.

If you were writing html for a web page before this, you might notice that it may be hard to actually tell what the content of your page will look like. The structure for a typical html page may be composed of mostly ```<div>``` tags like the following (I will omit everything outside of the body tag to simplify the example):

```
<body>
  <div>
  </div>
  <div>
  </div>
  
  <div>
    <div></div>
    <div></div>
    <div></div>
  </div>
  
  <div>
  </div>
</body>
```

Of course, it's hard to understand this example without the content inside of these tags. But with semantic html elements, we can easily see what tags are supposed to do what:

```
<body>
  <header></header>
  <nav></nav>
  
  <div>
    <section></section>
    <article></article>
    <aside></aside>
  </div>
  
  <footer></footer>
</body>
```

### Attributes
Html tags on their own are very limited, and this will especially be noticed when we talk about how to style elements with CSS. An attribute will look like the following:

```<tagName attribute="">```

These attributes provide additional information about the elements. They are always specified in the opening html tags. 

##  CSS
What is CSS? CSS stands for Cascading Style Sheets and it is used to help style a web document.

CSS is used as a set of rules to create a style on the user interface. This could be changing colors, fonts, or size of different elements on a page. HTML defines the content of the page, and CSS allows you to make it pretty.

### How to apply css styling
Within html, there is an attribute to add styling

##  Helpful Resources
Free Code Camp is a great website to walk your through examples! At the end of each certificate you must create a project using the tools that you learned. Certifcates from 
Free Code Camp are great to put on resume since it shows that you are familiar with many languages in frontend development.
https://www.freecodecamp.org/
