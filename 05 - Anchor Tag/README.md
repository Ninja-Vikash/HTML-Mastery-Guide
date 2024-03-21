##### HTML Mastery Guide 🏅
# Anchor Tag
### What's Inside
- What is an Anchor (`<a>`) tag?
- Major roles of Anchor tag
- Commonly used attributes with anchor tag
- `<iframe>` tag

***
## Overview
### What is an Anchor tag?
An anchor tag is used to render a **"Hypertext link"** using the `href` attribute. It can link to **Web Pages**, **files**, **email addresses**, **locations** on the same page, or anything else a URL can address. 

> [!IMPORTANT]\
> An anchor tag is an inline element.

```html
<a href="URL">Click Here!</a>
```
### Major roles of Anchor tag
#### To address html pages or any other document.
In `href` give the relative path of `about.html` file.
```html
<a href="about.html">About Us</a>
```
In `href` give the relative path of `contact.html` file.
```html
<a href="contact.html">Contact</a>
```
#### Folder structure
```
📁05 - Anchor Tag
└── about.html
└── contact.html
└── image.jpeg
└── index.html
└── README.md
```
#### To address any other webpage on the internet.
In `href` use the web address of any website to open the webpage. 
```html
<a href="https://www.google.com">Google</a>
```

#### Anchor used to link any section of webpage
```html
<a href="#bottom">Move to bottom</a>
```
> [!NOTE]\
> We can link any section using id's

### Commonly used attributes with anchor tag
#### href attribute
`href` attribute is a required attribute for anchor tags.
> [!WARNING]\
> Without href attribute anchor tag acts like a normal tag
#### target attribute
`target` attribute is used to define where to open the given path.

Generally used value with `target` attribute are-
```html
target= "_blank"
```
To learn more about anchor tag attributes [explore🔍!](https://github.com/Ninja-Vikash/HTML-Mastery-Guide/tree/main/03%20-%20Attributes#anchor-tag-attributes)

## iframe tag

### How to Embed online videos on webpage?
We can Embed online videos through a corresponding `<iframe>`; tag.

> [!NOTE]\
> `<iframe>` tag  specifies an inline frame.\
> An inline frame is used to embed another document within the current HTML document.

---

### Process of Embedding Youtube Video on Your webpage!
Search for a video on `YOUTUBE`

![preview 1](https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/embed-1.png)

> Click on `Share`

![preview 2](https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/embed-2.png)
> Select the Embed option from them

> Just - paste it on your HTML file

![preview 3](https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/embed-3.png)
![preview 4](https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/embed-4.png)
