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
To start, the root tag is is opened as ```<tag>``` and closed as ```</html>```. This tag is the root element of the HTML tree. All tags open with <tag> and close with </tag>. Here is an example of a very simple html file:

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

There are a wide range of tags in html. I will list and explain the most important ones here, as well as describe a little bit about the tags. For a full list of tags, visit
[this link](https://www.w3schools.com/TAGS/default.ASP). HTML tags are rectangular and often take up more space than the content inside of them.

As you can see, the tag actually takes up much more space on the page than just displaying the content. We will talk more about this once we move to the CSS Section. A large distinction to make between html elements is that some elements are block elements and some are inline. The characteristics of a block element are that it always starts on a new line, and it takes up as much space that is available. Inline elements differ because they do not start on new lines, and they take up only the space on the page that they need.

I am going to list some tags here and link you to the w3 school page explaining each of them. These are the most important tags to learn and will be most commonly used when developing web pages:

[```<a>```](https://www.w3schools.com/TAGS/tag_a.asp)<br />
[```<button>```](https://www.w3schools.com/TAGS/tag_button.asp)<br />
[```<body>```](https://www.w3schools.com/TAGS/tag_body.asp)<br />
[```<div>```](https://www.w3schools.com/TAGS/tag_div.asp)<br />
[```<form>```](https://www.w3schools.com/TAGS/tag_form.asp)<br />
[```<h1> - <h6>```](https://www.w3schools.com/TAGS/tag_hn.asp)<br />
[```<head>```](https://www.w3schools.com/TAGS/tag_head.asp)<br />
[```<html>```](https://www.w3schools.com/TAGS/tag_html.asp)<br />
[```<img>```](https://www.w3schools.com/TAGS/tag_img.asp)<br />
[```<input>```](https://www.w3schools.com/TAGS/tag_input.asp)<br />
[```<li>```](https://www.w3schools.com/TAGS/tag_li.asp)<br />
[```<link>```](https://www.w3schools.com/TAGS/tag_link.asp)<br />
[```<meta>```](https://www.w3schools.com/TAGS/tag_meta.asp)<br />
[```<ol>```](https://www.w3schools.com/TAGS/tag_ol.asp)<br />
[```<p>```](https://www.w3schools.com/TAGS/tag_p.asp)<br />
[```<script>```](https://www.w3schools.com/TAGS/tag_script.asp)<br />
[```<span>```](https://www.w3schools.com/TAGS/tag_span.asp)<br />
[```<style>```](https://www.w3schools.com/TAGS/tag_style.asp)<br />
[```<table>```](https://www.w3schools.com/TAGS/tag_table.asp)<br />
[```<tbody>```](https://www.w3schools.com/TAGS/tag_tbody.asp)<br />
[```<td>```](https://www.w3schools.com/TAGS/tag_td.asp)<br />
[```<th>```](https://www.w3schools.com/TAGS/tag_th.asp)<br />
[```<thead>```](https://www.w3schools.com/TAGS/tag_thead.asp)<br />
[```<tr>```](https://www.w3schools.com/TAGS/tag_tr.asp)<br />
[```<ul>```](https://www.w3schools.com/TAGS/tag_ul.asp)<br />
[```<video>```](https://www.w3schools.com/TAGS/tag_ul.asp)<br />

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

These attributes provide additional information about the elements. They are always specified in the opening html tags. They usually are declared like this ```name="value"```

##  CSS
What is CSS? CSS stands for Cascading Style Sheets and it is used to help style a web document.

CSS is used as a set of rules to create a style on the user interface. This could be changing colors, fonts, or size of different elements on a page. HTML defines the content of the page, and CSS allows you to make it pretty. To define a CSS file, you can end your file with the .css extension.

### CSS Syntax

CSS follows a very simple syntax. You are defining the rules for how elements on your page should be styled. You can write as many rules as you'd like. The syntax for writing rules is as follows:

```
 selector {
  property: value;
 }
```

Let's break this down piece by piece. The selector points to an element, class or id that you would like to style. The content contained within the curly-braces is called a declaration block. This is a set of property: value pairs separated by semicolons. Properties are the style you would like to change, and the value is the value you would like to set to that property. The following HTML and CSS codeblock will show you how element selectors, class and id's work within an html document

```
<head>
 <style>
   <!-- Set all p tags to have text color red -->
   p {
     color: red;
   }
   
   <!-- Set all tags with the class class-example to have a font-size of 30px -->
   .class-example {
     font-size: 30px;
   }
   
   <!-- Set the element with id id-example to have a background color of red -->
   #id-example {
     background-color: red;
   }
 </style>
</head>

<body>
  <div id="class-example">
    <h1 id="id-example">Hello</h1>
    <p>This is red text</p>
  </div>
</body>
```
Some important things to note with this example: 

```ID's``` are unique, so only one element can have an ID assigned to it. This is the most specific selector as it only targets one element<br />
```Classes``` can be applied to as many elements as you want, and it does not matter what element, it will apply the style to that specific element if the class is applied<br/>
```Element``` selectors target a specific tag, so in this case, all p tags in the above document would have the style applied to them.

### Cascading Style Sheets
The cascading part of CSS comes from the priority that styles rules are applied. CSS is read top to bottom, and there is a very real possibility that you might have a conflicting style. Look at the example below:

```
<head>
 <style>
   p {
     color: red;
   }
   
   p {
     color: green;
   }

 </style>
</head>

<body>
    <p>This is red text</p>
</body>
```

What color would you expect the p tag to be? In this case, because the second rule applied to p tags is lower in the document, the color would be green.

#### Inline Styling
There are several ways that you can apply styling to elements, within your html document, you can write inline styles using the style attribute. Doing this, your tag might look something like this:

```<p style="color:red;">This is a red paragraph.</p>```

This format of styling is great to easily add a style or two, but it is easy to see that this method may become confusing when many styles are applied to each tag. This leads us into a better way to structure CSS.

#### The style tag
To avoid writing CSS styles inline, which can cause your markup to be less readable, html provides a style tag. Here, you can write CSS and it will apply directly to your html document.
#### Using a separate CSS file
Using a separate CSS file is a great way to further re-use your CSS. Think about making a website, and you want the styling to be consistent across the site. Instead of copying and pasting your style tag into each document. Re-using styles is great and can help you easily change the whole style of your website later on if you decide you want to change something like the color scheme.

You can link an external stylesheet with the following html tag inserted into your head document (make sure the file you specify has the correct path to it)

```
<link rel="stylesheet" type="text/css" href="index.css">
```

The rel attribute specifies you are linking a stylesheet, the type attribute specifies that it is css, and the href attribute is a link to your css file.
##  Helpful Resources
[Free Code Camp](https://www.freecodecamp.org/) is a great website to walk your through examples! At the end of each certificate you must create a project using the tools that you learned. Certifcates from 
Free Code Camp are great to put on resume since it shows that you are familiar with many languages in frontend development.

[W3 Schools](https://www.w3schools.com/html/html_attributes.asp) is an excellent resource to go to when you have specific questions about different HTML or CSS related tags, properties or concepts as a whole. There is comprehensive documentation, and examples on how to use almost everything.

[The Odin Project](https://www.theodinproject.com/) is a collection of resources which will help you build up your web development skills with comprehensive exercises. It is a great way to get started with learning web development.
