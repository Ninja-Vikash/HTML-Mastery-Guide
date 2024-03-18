##### HTML Mastery Guide 🏅
# Fundamental & HTML Entity

In HTML, the tags and attributes are not case-sensitive. This means that you can use uppercase or lowercase letters when writing HTML elements, and the browser will interpret them in the same way. For example, `<p>`, `<P>`, and `<P>` are all considered the same and will create a paragraph element.

## Content table
- [Fundamental](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/02%20-%20Fundamentals#fundamental)
- [Element](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/02%20-%20Fundamentals#what-is-an-html-element)
- [Most Used Tags](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/02%20-%20Fundamentals#most-used-tags)
- [HTML Entity](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/02%20-%20Fundamentals#list-of-html-entities)

## Fundamental
### HTML is not case sensitive

```html
<html> = <HTML>
<p> = <P>
<head> = <HEAD>
<body> = <BODY>
```

### What is an HTML element?
Almost every html tag enclosed with an open and a closing tag.

```html
<start-tag>context<end-tag>
```
   
### Most used tags
#### For writing
```html
<p>This is a paragraph</p>
```
> [!NOTE]\
> `<p>` used to write paragraphs or normal text. It creates a new line before and after the element, taking up the full width of its parent container.
```html
<pre>
   This is 
         pre
      tag
</pre>
```
> [!NOTE]\
> `<pre>` tag is used for pre-formatted text, keeping the original spaces and line breaks exactly as they are in the code.

#### For Headings
```html
<h1>Heading h1</h1>
<h2>Heading h1</h2>
<h3>Heading h1</h3>
<h4>Heading h1</h4>
<h5>Heading h1</h5>
<h6>Heading h1</h6>
```
> [!NOTE]\
> When writing headings, the size of the text will decrease from `<h1>` (The most important heading and largest size) to `<h6>` (The least important heading and smallest size).

#### For Text Formatting
**Bold**
```html
<b>I am Bold</b>
```
> [!NOTE]\
> `<b>` tag is used to make text bold
```html
<i>I am Italic</i>
``` 
> [!NOTE]\
> `<i>` tag is used to make text italic

```html
<u>I am Underline</u>
```
> [!NOTE]\
> `<u>` tag is used to make underline

> [!IMPORTANT]\
> `<strong>` tag is similar to the `<b>` tag and `<em>` tag is similar to the `<i>` tag.


```html
<big>I am big</big>
<small>I am small</small>
```

```html
<sup>I am Superscript</sup>
<sub>I am Subscript</sub>
``` 
***
> [!NOTE]\
> Sometimes we use some special characters on a web page like angular brackets, copyright symbols, trademark symbols, etc.\
> But there is a problem with HTML we can't use angular brackets directly because HTML takes them as a tag, if we use opening and closing angular brackets together it will affect our code. To solve this bug we will use **HTML Entity** \
> It starts with Ampersand (&) and should be closed with a semi-colon (;),

### List of HTML Entities
```html
● &nbsp; - Non-breaking space
● &lt; - Less than angular bracket
● &gt; - Greater than angular bracket
● &copy; - Copyright 
● &amp; - Ampersand 
● &semi; - SemiColon 
● &reg; - Registered 
● &trade; - Trademark 
● &commat; - At the rate 
● &star; - Holo Star
● &starf; - Filled Star
● &phone; - Phone 
● &male; - Male 
● &female; - Female 
● &hearts; - Heart 
● &spades; - Spade
● &clubs; - Club
● &diams; - Diamond
● &sung; - Tune 
● &check; - Check
```
<p>There are so many symbols in HTML we can use them to add # after &</p>

#### Contributions are welcome ❤️
### Happy Coding 🤝!
