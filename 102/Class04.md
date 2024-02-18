# Structure web pages with HTML

## What is HTML and why do we use it?

+ HTML stands for Hyper Text Markup Language
+ HTML is the standard markup language for creating Web pages
+ HTML describes the structure of a Web page
+ HTML consists of a series of elements
+ HTML elements tell the browser how to display the content
+ HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

Using HTML, you can define headers, paragraphs, links, images, and more, so your browser knows how to structure the web page you're looking at.

## What are the 3 main parts of an HTML element?

An HTML element is defined by a start tag, some content, and an end tag:

< p > My cat is very grumpy< / p >

+ Openning tagname '< p >' 

+ Content 'My cat is very grumpy'

+ Closing tagname ' < / p > '

The HTML element is everything from the start tag to the end tag:

'< h1 > My First Heading < /h1 >'

'< p > My First Paragraph< /p >''

## What is it called when you give an element extra information?

![grumpy-cat-attribute-small](https://github.com/Ssanthoshp/reading-notes/assets/153047977/a5f8aa48-5014-4e0f-8aee-dfb7ba443d59)

Attributes contain extra information about the element that you don't want to appear in the actual content. Here, class is the attribute name and editor-note is the attribute value. The class attribute allows you to give the element a non-unique identifier that can be used to target it (and any other elements with the same class value) with style information and other things. Some attributes have no value, such as required.

Attributes that set a value always have:

A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
The attribute name followed by an equal sign.
The attribute value wrapped by opening and closing quotation marks.

## What is a semantic element?

A semantic element clearly describes its meaning to both the browser and the developer. 

Examples of non-semantic elements: < div > and < span > - Tells nothing about its content. 

Examples of semantic elements: < form > , < table > , and < article > - Clearly defines its content.

For more information, please refer to [link](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
