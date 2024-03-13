##### HTML Mastery Guide

# Attributes in HTML

### What is an Attribute in HTML tags?

**Attributes** play a crucial role in HTML tags by providing additional information about the elements. They are used to modify the behavior or appearance of HTML elements, making them more versatile and functional. Attributes are always included within the opening tag of an HTML element and are written as name-value pairs.

> [!NOTE]\
> Attributes are used to give some additional functionality to an HTML tag.

## What's Inside
- [**Role of Attributes**](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/03%20-%20Attributes#role-of-attributes)
- [**Attribute Table**](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#attribute-table)  
  * [Meta Tag Attributes](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/03%20-%20Attributes#meta-tag-attributes)
  * [Anchor Tag Attributes](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/03%20-%20Attributes#anchor-tag-attributes)
  * [Imgage Tag Attributes]()
  * [Video Tag Attributes]()
  * [Input Tag Attributes]()
- [**Special Attributes**]()
  * [Class]()
  * [Id]()
  * [Style]()

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
| `<meta>` | [charset](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#character-encoding) | UTF-8 | Specifies the character encoding for the HTML document. |
| `<meta>` | [viewport](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#viewport-settings-for-responsive-design) | width=device-width | Sets the width of the viewport to the device width, ensuring that the content fits the screen. |
| | | initial-scale=1.0 | Sets the initial zoom level when the page is loaded. A value of 1.0 means no zoom, and the content will be displayed at its actual size. |
| | | minimum-scale=0.7 | |
| | | maximum-scale=1.3 | |
| | [description](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#description-meta-tag) | HTML Mastery Guide | Provides a short description of the HTML document. Often used by search engines. |
| | [keywords](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#keywords-meta-tag) | HTML, CSS | Specifies a comma-separated list of keywords relevant to the page's content. |
| | [author](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#author-meta-tag) | Ninja-Vikash | Specifies the author of the HTML document.|
| | [robots](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#robots-meta-tag) | index, follow | Directs search engine crawlers on how to index and follow links on a page. |
| | [refresh](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#refresh-meta-tag-redirect-after-5-seconds) | 5;url=https://example.com | Redirects the page to another URL after a specified time (in seconds). |
| | [theme-color](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#theme-color-meta-tag) | #3498db | Sets the theme color for the browser's UI elements when the page is added to the home screen on mobile devices. |
| `<a>` | [href](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#href) | http://wwww.google.com/ | Specifies the URL (web address) of the linked resource.
| | | sample.html | |
| | [target](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#target) | _blank | Opens the link in a new tab or window. |
| | | _self | Opens the link in the same tab or window (default behavior). |
| | | _parent |  Opens the link in the parent frame. |
| | | _top | Opens the link in the full body of the window. |
| | [download](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#download) |  | Indicates that the linked resource should be downloaded rather than navigated to. |
| |  [rel](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#rel) | nofollow | Instructs search engines not to follow the link. |
| | | noopener | Prevents the new page from accessing the window.opener property. |
| | | noreferrer | Requires the browser not to send a referrer header. |
| | [title](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#title) | | Provides additional information about the linked resource, often displayed as a tooltip. |
| | [aria-label](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/blob/main/03%20-%20Attributes/README.md#aria-label) | | Specifies an accessible label for screen readers, providing additional context. |
| `<img>` | [src]() | image.jpg | Specifies the source URL of the image. This is a mandatory attribute. |
| | [alt]() | This is a sample image | Provides alternative text for the image, which is displayed if the image cannot be loaded or for accessibility purposes. |
| | [width]() | 300px | Specifies the width of the image in pixels |
| | [height]() | 200px | Specifies the height of the image in pixels |
| | [title]() | | Adds a title or tooltip that is displayed when the user hovers over the image. |
| | [loading]() | eager | Determines how the browser should load the image (eager is default value). |
| | | lazy | |
| | | auto | |
| | [style]() | | Allows you to apply inline CSS styles to the image. |
| `<video>` | [src]() | video.mp4 | Specifies the source URL of the video file. This is a mandatory attribute. |
| | [controls]() | | Adds basic video controls such as play, pause, and volume. |
| | [width]() | 300px | Sets the width of the video player in pixels. |
| | [height]() | 200px | Sets the height of the video player in pixels. |
| | [autoplay]() | | Specifies that the video should start playing automatically when the page loads. |
| | [loop]() | | Causes the video to play in a loop, restarting when it reaches the end. |
| | [muted]() | | Mutes the audio of the video by default. |
| | [poster]() | | Video thumbnail. |
| | [preload]() | auto | Indicates how the browser should preload the video. "auto" (default), "metadata" (preload only metadata), and "none" (do not preload).. |
| |  | metadata | "metadata" (preload only metadata) |
| |  | none | "none" (do not preload).. |
| | [playsinline]() | | Enables the video to play inline on mobile devices instead of in a full-screen mode. |
| `<input>` | [type]() | text | For taking text value |
| | | password | Value will appear in the form of * |
| | | checkbox | We can select more values |
| | | radio | We can choose only one |
| | | submit | For submitting |
| | | reset | For resetting |
| | | file | For inserting any file |
| | | email | Takes only email |
| | | number | Takes only numbers  |
| | [name]() | name | Provides a name for the input field. This name is used when submitting the form, and it should be unique within the form. |
| | [value]() | | Sets the initial value of the input field. For checkboxes and radio buttons, it represents the value that gets sent to the server when the form is submitted. |


### Meta Tag Attributes
#### Character Encoding
```html
<meta charset="UTF-8">
```
> Specifies the character encoding for the HTML document.

#### Viewport Settings for Responsive Design
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
> Defines the viewport settings, especially important for responsive web design.

#### Description Meta Tag
```html
<meta name="description" content="A brief description of the webpage">
```
> Provides a short description of the HTML document. Often used by search engines.

#### Keywords Meta Tag
```html
<meta name="keywords" content="HTML, CSS, web development">
```
> Specifies a comma-separated list of keywords relevant to the page's content.

#### Author Meta Tag
```html
<meta name="author" content="John Doe">
```
> Specifies the author of the HTML document.

#### Robots Meta Tag
```html
<meta name="robots" content="index, follow">
```
> Directs search engine crawlers on how to index and follow links on a page.

#### Refresh Meta Tag (Redirect after 5 seconds)
```html
<meta http-equiv="refresh" content="5;url=https://example.com">
```
> Redirects the page to another URL after a specified time (in seconds).

#### Theme Color Meta Tag
```html
<meta name="theme-color" content="#3498db">
```
> Sets the theme color for the browser's UI elements when the page is added to the home screen on mobile devices.

***
### Anchor Tag Attributes
#### href
```html
<a href="https://www.example.com">Visit Example.com</a>
```
> Specifies the URL (web address) of the linked resource.

#### target
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

#### download
```html
<a href="document.pdf" download>Download PDF</a>
```
> Indicates that the linked resource should be downloaded rather than navigated to.

#### rel
```html
<a href="https://www.example.com" rel="nofollow">Visit Example.com</a>
```
> Specifies the relationship between the current document and the linked document.

> [!NOTE]\
> We have few values to use in `rel` attribute\
> `nofollow` : Instructs search engines not to follow the link.\
> `noopener` : Prevents the new page from accessing the window.opener property.\
> `noreferrer` : Requires the browser not to send a referrer header.

#### title
```html
<a href="https://www.example.com" title="Visit Example.com">Link</a>
```

> Provides additional information about the linked resource, often displayed as a tooltip.

#### aria-label
```html
<a href="https://www.example.com" aria-label="Visit Example.com">Link</a>
```
> Specifies an accessible label for screen readers, providing additional context.

***
### Image Tag Attributes
In HTML (Hypertext Markup Language), the `<img>` tag is used to embed images in a web page. The img tag has several attributes that allow you to control various aspects of the image display. Here are some common image tag attributes
#### src (required)
```html
<img src="image.jpg" alt="Description">
```
> [!IMPORTANT]\
> Specifies the source URL of the image. This is a mandatory attribute.

#### alt
```html
<img src="image.jpg" alt="Description of the image">
```
> Provides alternative text for the image, which is displayed if the image cannot be loaded or for accessibility purposes.

#### width & height
```html
<img src="image.jpg" alt="Description" width="300" height="200">
```
> Specifies the width and height of the image in pixels. These attributes help control the layout of the page, and specifying them can prevent the page from reflowing as the image loads.

#### title
```html
<img src="image.jpg" alt="Description" title="Additional information">
```
> Adds a title or tooltip that is displayed when the user hovers over the image.

#### loading (HTML5)
```html
<img src="image.jpg" alt="Description" loading="lazy">
```
> [!NOTE]\
> Determines how the browser should load the image. Possible values are "eager" (default), "lazy", or "auto".

#### style
```html
<img src="image.jpg" alt="Description" style="border: 1px solid black;">
```
> Allows you to apply inline CSS styles to the image.

> [!NOTE]\
> We will study about styling in the CSS repository.

### Video Tag Attribute
The `<video>` tag in HTML is used to embed video content in a web page. It has various attributes that allow you to control the behavior and appearance of the video player. Here are some common attributes for the `<video>` tag:
#### src (required)
```html
<video src="video.mp4" controls></video>
```
> [!IMPORTANT]\
> Specifies the source URL of the video file. This is a mandatory attribute.

#### controls
```html
<video src="video.mp4" controls></video>
```
> [!NOTE]\
> Adds basic video controls such as play, pause, and volume.

#### width and height
```html
<video src="video.mp4" width="640" height="360" controls></video>
```
> Sets the width and height of the video player in pixels.

#### autoplay
```html
<video src="video.mp4" autoplay></video>
```
> Specifies that the video should start playing automatically when the page loads.

#### loop
```html
<video src="video.mp4" loop></video>
```
> Causes the video to play in a loop, restarting when it reaches the end.

#### muted
```html
<video src="video.mp4" muted></video>
```
> Mutes the audio of the video by default.

#### poster
```html
<video src="video.mp4" poster="poster-image.jpg" controls></video>
```
> [!NOTE]\
> Specifies an image to be displayed as the poster (or placeholder) for the video before it starts playing.\
> As a thumbnail.

#### preload
```html
<video src="video.mp4" preload="auto"></video>
```
> Indicates how the browser should preload the video. Possible values are "auto" (default), "metadata" (preload only metadata), and "none" (do not preload).

#### playsinline
```html
<video src="video.mp4" playsinline></video>
```
> Enables the video to play inline on mobile devices instead of in a full-screen mode.

### Input Tag Attribute
The `<input>` tag in HTML is a versatile element used to create various form controls. The behavior and appearance of these controls can be customized using different attributes. Here are some common attributes for the `<input>` tag

#### type (required)
```html
<input type="text" name="username">
```
> [!IMPORTANT]\
> Specifies the type of form control to be created. Common values include\
> "text", "password", "checkbox", "radio", "submit", "reset", "file", "email", "number", and more.

#### name
```html
<input type="text" name="username">
```
> [!NOTE]\
> Provides a name for the input field. This name is used when submitting the form, and it should be unique within the form.

#### value
```html
<input type="text" name="username" value="JohnDoe">
```
> Sets the initial value of the input field. For checkboxes and radio buttons, it represents the value that gets sent to the server when the form is submitted.

#### placeholder
```html
<input type="text" name="username" placeholder="Enter your username">
```
> Specifies a short hint that describes the expected value of the input field. It is typically displayed before the user enters a value.

#### disabled
```html
<input type="text" name="username" disabled>
```
> Disables the input field, making it non-editable and preventing user interaction.

#### readonly
```html
<input type="text" name="username" value="JohnDoe" readonly>
```
> Makes the input field read-only, preventing the user from modifying its value, but still allowing it to be submitted with the form.

#### required
```html
<input type="text" name="username" required>
```
> [!NOTE]\
> Specifies that the input field must be filled out before submitting the form.

#### maxlength
```html
<input type="text" name="username" maxlength="20">
```
> Sets the maximum number of characters allowed in the input field.

#### min and max
```html
<input type="number" name="age" min="18" max="99">
```
> For number and date inputs, specifies the minimum and maximum allowed values.

#### pattern
```html
<input type="text" name="zipcode" pattern="[0-9]{5}">
```
> Specifies a regular expression pattern that the input value must match for the form to be submitted.

These are just a few of the many attributes you can use with the `<input>` tag. The specific attributes you use depend on the type of form control you are creating and the desired behavior of your form.

## Special Attribute
The attributes mentioned are applicable to various HTML tags and are commonly implemented across different elements.
### class
The `class` attribute in HTML is used to assign one or more class names to an HTML element. The primary role of the class attribute is to provide a way to apply styles and behaviors to multiple elements on a web page. It allows you to create a reusable set of styles or scripts and apply them to different elements without having to duplicate the code.

- **Styling with CSS**

  By assigning a class to an HTML element, you can target that class in your CSS (Cascading Style Sheets) to apply specific styles. This promotes a separation of concerns between the structure (HTML), presentation (CSS), and behavior (JavaScript) of a web page.

  ```html
  <style>
    .highlight {
      background-color : yellow;
    }
  </style>
  
  <p class="highlight">This paragraph has a yellow background</p>
  ```
- **JavaScript and DOM Manipulation**

  JavaScript can use the `class` attribute to select and manipulate elements in the Document Object Model (DOM). This is particularly useful when adding or removing classes dynamically based on user interactions or other events.

  ```html
  <script>
    function toggleHighlight() {
      var element = document.getElementById("myElement");
      element.classList.toggle("highlight");
    }
  </script>

  <button onclick="toggleHighlight()">Toggle Highlight</button>
  <p id="myElement">This paragraph can be highlighted.</p>
  ```

- **Styling Frameworks and Libraries**

  Many CSS frameworks and libraries, such as tailwindCSS, use the `class` attribute extensively to provide pre-defined styles. By applying specific classes, you can easily leverage the styling and layout features provided by these frameworks.

  ```html
  <h1 class="text-xl font-bold text-center">Hello World!</h1>
  ```

> [!IMPORTANT]\
> Using the `class` attribute in HTML allows for a more modular and maintainable approach to styling and scripting, making it easier to update the appearance and behavior of multiple elements throughout a website.

### id
The `id` attribute in HTML is used to uniquely identify an individual HTML element on a web page. Unlike the `class` attribute, which is designed for grouping multiple elements together, the `id` attribute should be assigned to a single element. 

The primary roles and purposes of the `id` attribute are as follows
- **Uniqueness**

  The primary role of the `id` attribute is to provide a unique identifier for a specific HTML element within a document. Each `id` value must be unique within the HTML document to ensure that it refers to only one specific element.

  ```html
  <div id="header">This is the header</div>
  <p id="main-content">This is the main content</p>
  ```

- **Styling with CSS**

  Similar to the `class` attribute, the `id` attribute is often used in conjunction with CSS to apply specific styles to an individual element. The `id` selector in CSS begins with a hash (`#`) followed by the `id` value.

  ```html
  <style>
    #header {
      font-size: 20px;
      color: blue;
    }
  </style>

  <div id="header">This is the styled header</div>
  ```

- **JavaScript and DOM Manipulation**
  
  The `id` attribute is frequently used in JavaScript for selecting and manipulating specific elements in the Document Object Model (DOM). This is valuable for dynamic web pages and interactivity, allowing developers to target and modify individual elements.

  ```html
  <script>
    var headerElement = document.getElementById("header");
    headerElement.innerHTML = "Updated header text";
  </script>

  <div id="header">This is the original header</div>
  ```

- **Anchors and Links**

  The `id` attribute is often used in combination with fragment identifiers in URLs to create anchor links. This allows users to navigate directly to a specific section or element within a page.

  ```html
  <a href="#main-content">Jump to Main Content</a>
  <p id="main-content">This is the main content</p>
  ```

> [!IMPORTANT]\
> It's important to note that while the class attribute can be used for multiple elements, the id attribute should be unique within the document. Overusing id values or assigning the same id to multiple elements can lead to issues and is generally not recommended.

### style
The `style` attribute in HTML is used to apply inline styles directly to a specific HTML element. It allows you to define CSS (Cascading Style Sheets) properties for that particular element without the need for an external stylesheet. The `style` attribute takes a string value containing one or more CSS property-value pairs separated by semicolons.

- **Element-Specific Styling**

  The `style` attribute allows you to apply styling directly to a specific HTML element. This is useful when you want to define styles for a single element without affecting other elements on the page.

- **Dynamic Styling**

  Inline styles can be modified dynamically using JavaScript. This is particularly useful for interactive web pages where the appearance of an element may change based on user interactions or other events.

  ```html
  <button onclick="changeColor()">Change Color</button>
  <p id="myParagraph" style="color: blue;">This paragraph has inline styles.</p>

  <script>
    function changeColor() {
      var paragraph = document.getElementById("myParagraph");
      paragraph.style.color = "green";
    }
  </script>
  ```

- **Quick Styling for Prototyping**
  
  The `style` attribute is convenient for quickly adding styles during the development and prototyping phase when you may not have a fully developed CSS file.

  ```html
  <div style="border: 1px solid black; padding: 10px; background-color: #f0f0f0;">Styled div</div>
  ```

- **Specificity**

  Inline styles have a high level of specificity in the CSS cascade. If conflicting styles are applied to an element, the inline styles will usually take precedence over styles defined in an external stylesheet or a style block.

> [!IMPORTANT]\
> Specificity order for styling elements\
> Type Selector < Class Selector < ID Selector < Inline Style\
> Specificity order of styles where it written\
> Inline > Internal > External

> [!NOTE]\
> We we add `!important` at the end of any property of CSS, It will override even inline style.
```html
<style>
  h2 {
      text-align: center !important;
  }
</style>
```

Despite its convenience, it's generally recommended to use external stylesheets or style blocks in the `<head>` section of the HTML document for larger projects. This promotes a cleaner separation of HTML structure and CSS styles, making the code more maintainable and easier to manage.


----------------------------------------------------------------------------------------------------------
## URL(Uniform Resource Locator)
### What is URL?
URL stands for Uniform Resource Locator. Any internet location available on the server is called a web URL, web address, or website. URL gives the address of files created for webpages or other documents like an image, pdf for a doc file, etc.

**There are two types of URLs**
1. [Absolute URL](https://www.geeksforgeeks.org/types-of-url/#absolute-url)
2. [Relative URL](https://www.geeksforgeeks.org/types-of-url/#relative-url)

### Absolute URL
This type of URL contains both the domain name and directory/page path. An absolute URL gives complete location information. It begins with a protocol like `https://` and continues, including every detail.

### Relative URL
This type of URL contains the path excluding the domain name. Relative means “in relation to”, and a relative URL tells a URL location in terms of the current location. A relative path is used for reference to a given link of a file that exists within the same domain.

Let us assume a web developer setting up a webpage and want to link an image called
`<img src="img.jpeg">`

#### Contributions are welcome ❤️
### Happy Coding 🤝!