# 1. Front-End-Development: HTML

## 1.1: Structure
### How the web works
- When you visit a website, the web server hosting that site could be anywhere in the world.
- To find the location of the server it is first connected to a Domain Name System (DNS) server.

1. When you connect to the web, you do so via an Internet Service Provider (ISP).
   
2. Your computer contacts a network of services called Domain Name System (DNS) servers.
   - They tell your computer the IP address associated with the requested domain name.
   - Every device on the web has it's own IP address; it is like a phone number for a computer
     
3. The unique number that the DNS server returns to your computer allows your browser to contact the web server that hosts the website you requested.
   - A web server is a computer that is constantly connected to the web, and is set up to send web pages to users.
     
4. The web server then sends the page you requested back to your browser.

### HTML describes the structure of pages
```html
<html>
   <body>
      <h1> Main heading </h1>
      <p>
         This box can be used to write a paragraph
      </p>
      <h2> Sub heading </h2>
      <p>
         Another paragraph box
      </p>
   </body>
</html>
```

- HTML code (in blue) is made up of characters that live inside brackets - also called HTML elements.

### Attributes tell us more about elements
- Attributes provide information about the contents of an elements
- They appear on the opening tag of the element and are made up of two parts: a name and a value (seperated by = sign)

```html
<p lang="en-us">Paragraph in English</p>
```
- Here an attribute called lang is used to indicate the language in this element. The value of this attribute on this page specifies US English.
  
#### Attribute name (lang)
- Indicates the kind of extra information being supplised about the elements content.

#### Attribute value (en-us)
- Information of setting for the attribute.

```html
<p lang="en-fr">Paragraph in French</p>
```
### Summary Chapter 1: Structures

- HTML pages are text documents.
- HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning.
- Tags are often referred to as elements.
- Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes end.
- Opening tags can carry attributes, which tell us more about the content of that element.
- Attributes require a name and a value.
- To learn HTML you need to know what tags are avaulable for you to use, what they do, and where they can go.

## 1.2: Text
- The chapter focuses on how to add markup to text that appears on pages.

## Structural Markup
- Elements that you can use to describe both heading and paragraphs

### Headings
- HTML has six levels of headings:
``` html
<h1>Main headings</h1>
<h2>Sub headings</h2>
<h3>level 3</h3>
<h4>level 4</h4>
<h5>level 5</h5>
<h6>level 6</h6>
```

### Bold & Italic
```html
<b>Bold</b>
<i>Italic</i>

<sup>Superscript</sup>
<sub>Subscript</sub>
```


### Line breaks & horizontal lines
```html
<br />

<p> The Earth <br /> gets one hundred tons heavier every day </p>
<hr />
```

## Semantic Markup
- Provides extra information; such as wehere emphasis is placed in a sentence

### Strong & Emphasis
```html
<p><strong>Beware: </strong> Pickpockets operate in this aeara </p>
<p> I <em> think </em> Ivy was the first </p>
```

### Quatations 
```html
<blockquote cite="https://www.w3resource.com/java-exercises/index-inheritance.php#editorr">
<p>Java is an Object Oriented program</p>
</blockquote>

<p> Michael said, <q>Let's play blackjack</q></p>
```

### Abbreviations & Acryonyms
```html
<p><abbr title="Professor">Prof</abbr> Michael Moser is a computer engineer.</p>

```

### Author Details
```html
<address>
   <p><a href="mailto:mmoser@bell.net">
      mmoser@bell.net</a></p>
</address>
```

### Changes to Content
``` html
<p> It was the <del>worst</del> <ins>best</ins> idea I ever had </p>

<p> Laptop </p>
<p> <s> Was $990 </s> </p>
<p> Now only $300 </p>

```

### Summary Chapter 2: Text 
- HTML elements are used to describe the structure of the page (headings, subheadings, paragraphs).
- They also provide semantic information (where emphasis should be placed, the definition of any acronyms used, when given text is quotation).

















