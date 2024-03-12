##### HTML Mastery Guide

# Attributes in HTML

### What is an Attribute in HTML tags?

**Attributes** play a crucial role in HTML tags by providing additional information about the elements. They are used to modify the behavior or appearance of HTML elements, making them more versatile and functional. Attributes are always included within the opening tag of an HTML element and are written as name-value pairs.

> [!NOTE]\
> Attributes are used to give some additional functionality to an HTML tag.

## Content Table
- [**Role of Attributes**](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/03%20-%20Attributes#role-of-attributes)
- [**Attribute Table**]()  
  * [Meta Tag Attributes](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/03%20-%20Attributes#meta-tag-attributes)
  * [Anchor Tag Attributes](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/03%20-%20Attributes#anchor-tag-attributes)
  * [Imgage Tag Attributes]()


### Role of Attributes

- **Providing Information**

  Attributes supply extra information about the content or behavior of an HTML element. For example, the `alt` attribute in the `<img>` tag provides alternative text for an image, aiding accessibility.

  ```html
  <img src="example.jpg" alt="A descriptive text">
  ```
- **Controlling Element Behavior**

  Attributes can control how an element behaves or interacts with users. The `href` attribute in the `<a>` tag determines the hyperlink destination, and the `target` attribute controls where the linked content is opened.

  ```html
  <a href="https://www.example.com" target="_blank">Visit Example.com</a>
  ```

- **Defining Style**

  Attributes can be used to define the visual style of an element. The `style` attribute in various tags allows you to apply inline CSS styles directly to the element.

  ```html
  <p style="color: blue; font-size: 16px;">This is a styled paragraph.</p>
  ```

- **Handling Forms**

  Attributes are crucial in form elements, influencing how user input is processed. The `type` attribute in `<input>` determines the input type, such as text, password, or checkbox.

  ```html
  <input type="text" name="username" placeholder="Enter your username">
  ```

- **Providing Metadata**

  Certain attributes are used for providing metadata about the document or elements. The `charset` attribute in the `<meta>` tag specifies the character encoding for the document.

  ```html
  <meta charset="UTF-8">
  ```

- **Enabling JavaScript Interaction**

  Attributes like `id` and `class` are often used to uniquely identify or group elements, making it easier to manipulate them using JavaScript or apply styles with CSS.

  ```html
  <div id="uniqueId" class="styledBox">This is a uniquely identified and styled div.</div>
  ```
Attributes enhance the flexibility and functionality of HTML elements, making them more adaptable to different requirements in web development. Understanding how to use attributes effectively is essential for creating well-structured and dynamic web pages.

***

### Attribute Table

|<div style="width: 5vw">Tag</div>| <div style="width: 7vw">Attribute</div> | <div style="width: 15vw">Value</div> | <div>Role</div> |
| --- | --- | -- | -- |
| `<meta>` | [charset]() | UTF-8 | Specifies the character encoding for the HTML document. |
| `<meta>` | [viewport]() | width=device-width | Sets the width of the viewport to the device width, ensuring that the content fits the screen. |
| | | initial-scale=1.0 | Sets the initial zoom level when the page is loaded. A value of 1.0 means no zoom, and the content will be displayed at its actual size. |
| | | minimum-scale=0.7 | |
| | | maximum-scale=1.3 | |
| | [description]() | HTML Mastery Guide | Provides a short description of the HTML document. Often used by search engines. |
| | [keywords]() | HTML, CSS | Specifies a comma-separated list of keywords relevant to the page's content. |
| | [author]() | Ninja-Vikash | Specifies the author of the HTML document.|
| | [robots]() | index, follow | Directs search engine crawlers on how to index and follow links on a page. |
| | [refresh]() | 5;url=https://example.com | Redirects the page to another URL after a specified time (in seconds). |
| | [theme-color]() | #3498db | Sets the theme color for the browser's UI elements when the page is added to the home screen on mobile devices. |
| `<a>` | [href]() | http://wwww.google.com/ | Specifies the URL (web address) of the linked resource.
| | | sample.html | |
| | [target]() | _blank | Opens the link in a new tab or window. |
| | | _self | Opens the link in the same tab or window (default behavior). |
| | | _parent |  Opens the link in the parent frame. |
| | | _top | Opens the link in the full body of the window. |
| | [download]() |  | Indicates that the linked resource should be downloaded rather than navigated to. |
| |  [rel]() | | Specifies the relationship between the current document and the linked document. |
| | [title]() | | Provides additional information about the linked resource, often displayed as a tooltip. |
| | [aria-label]() | | Specifies an accessible label for screen readers, providing additional context. |




### Meta Tag Attributes
**Character Encoding**
```html
<meta charset="UTF-8">
```
> Specifies the character encoding for the HTML document.

**Viewport Settings for Responsive Design**
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
> Defines the viewport settings, especially important for responsive web design.

**Description Meta Tag**
```html
<meta name="description" content="A brief description of the webpage">
```
> Provides a short description of the HTML document. Often used by search engines.

**Keywords Meta Tag**
```html
<meta name="keywords" content="HTML, CSS, web development">
```
> Specifies a comma-separated list of keywords relevant to the page's content.

**Author Meta Tag**
```html
<meta name="author" content="John Doe">
```
> Specifies the author of the HTML document.

**Robots Meta Tag**
```html
<meta name="robots" content="index, follow">
```
> Directs search engine crawlers on how to index and follow links on a page.

**Refresh Meta Tag (Redirect after 5 seconds)**
```html
<meta http-equiv="refresh" content="5;url=https://example.com">
```
> Redirects the page to another URL after a specified time (in seconds).

**Theme Color Meta Tag**
```html
<meta name="theme-color" content="#3498db">
```
> Sets the theme color for the browser's UI elements when the page is added to the home screen on mobile devices.

***
### Anchor Tag Attributes
**href**
```html
<a href="https://www.example.com">Visit Example.com</a>
```
> Specifies the URL (web address) of the linked resource.

**target**
```html
<a href="https://www.example.com" target="_blank">Visit Example.com</a>
```
> Specifies where to open the linked document.

> [!NOTE]\
> We have multiple values to use in `target` attribute\
> `_blank` : Opens the link in a new tab or window.\
> `_self` : Opens the link in the same tab or window (default behavior).\
> `_parent` : Opens the link in the parent frame.\
> `_top` :  Opens the link in the full body of the window.

**download**
```html
<a href="document.pdf" download>Download PDF</a>
```
> Indicates that the linked resource should be downloaded rather than navigated to.

**rel**
```html
<a href="https://www.example.com" rel="nofollow">Visit Example.com</a>
```
> Specifies the relationship between the current document and the linked document.

> [!NOTE]\
> We have few values to use in `rel` attribute\
> `nofollow` : Instructs search engines not to follow the link.\
> `noopener` : Prevents the new page from accessing the window.opener property.\
> `noreferrer` : Requires the browser not to send a referrer header.

**title**
```html
<a href="https://www.example.com" title="Visit Example.com">Link</a>
```

> Provides additional information about the linked resource, often displayed as a tooltip.

**aria-label**
```html
<a href="https://www.example.com" aria-label="Visit Example.com">Link</a>
```
> Specifies an accessible label for screen readers, providing additional context.



# Above


```html
<link rel="stylesheet" href="style.css">
```
`rel="stylesheet"` is the relation attribute.

```html
<img src="img.jpeg" alt="Book image">
```
`src="relative | absolute url"` is the source attribute, where we will paste the address of img.jpeg locally or the URL of the image from the web. Alt is an alternate attribute that is shown in the browser when somehow our image does not load on the web page. <br>
> For Those Tags without attributes, we can add attributes to give them some additional details to the HTML tag
```html
<img src="img.jpeg" alt="Book image" height="200px">
```
> We use only height or width on images to maintain their aspect ratio.

> Attributes usually come in name/value pairs like `name="value"`

We will learn about more attributes of tags in further chapters. like style attribute for inline styling, type attribute for input tags

## URL(Uniform Resource Locator)
URL stands for Uniform Resource Locator. Any internet location available on the server is called a web URL, web address, or website. URL gives the address of files created for webpages or other documents like an image, pdf for a doc file, etc.
<br>
There are two types of URLs-
1. Absolute
2. Relative

### Absolute URL
This type of URL contains both the domain name and directory/page path. An absolute URL gives complete location information. It begins with a protocol like `https://` and continues, including every detail.

### Relative URL
This type of URL contains the path excluding the domain name. Relative means “in relation to”, and a relative URL tells a URL location in terms of the current location. A relative path is used for reference to a given link of a file that exists within the same domain.
<br>
Let us assume a web developer setting up a webpage and want to link an image called
`<img src="img.jpeg">`


### Notable

```html
<img src="URL" />
```
 is a self-closing tag used to display Images on a screen.
```html
<video src="URL"></video>
```
has a closing tag used to display Videos on a screen.


<a href="https://github.com/Ninja-Vikash/HTML/tree/main/CHAPTER%204%20-%20Page%20Layout">
  <img src="https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/next-removebg-preview.png" height="30px" />
</a>
