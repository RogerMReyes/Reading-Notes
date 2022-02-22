# HTLM: Hyper Text Markup Language

Hypertext refers to links that conect web pages to one another.

## Anatomy of an HTML element

\<p>My cat is very grumpy\</p> 

The entire line above is the **Element**    
\<p> at the front is the **Opening Tag** while \</p> is the **Closing Tag**
The text inbetween the tags is known as the **Content**

**Attributes** contain extra information about the element that you don't want appearing in the actual content 

Putting elements within other elements is referred to as nested elements  
EX. wrapping a word with \<strong> with bold the word

## Anatomy of an HTML document
 
- \<!DOCTYPE html> is a required preamble to ensure everything works how it should
- \<html></html> wraps all the content on the page 
- \<head></head> container for all the stuff you don't want shown to the page's viewers
- \<meta charset="utf-8"> sets the character set for the document
- \<title></title> sets the title of your page which shows on the browsers tab
- \<body></body> contains all the content you want shown to the page's viewers

### Marking Up Text

- \<h1>–\<h6> specifies the level of heading
- \<!-- and --> any text within the arrows is ignored and is an HTML comment
- \<p> contains paragraphs
- \<ul> are Unordered Lists
- \<ol> are Ordered Lists
- \<li> will wrap each item withiin a list

### Links

To add a link first wrap your text with an \<a> element  
You will then add an href attribute with the webaddress inside double quotes after href  
Ex. \<a \href="htttps/">Mozilla Manifesto</a>
