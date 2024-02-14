# CHAPTER 9
## Forms in HTML <img src="https://github.com/Ninja-Vikash/asset-cloud/blob/main/icon%20%26%20png/htmlLogo.png" height="20px" />
![Banner](https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/HTML.png)

### What is form in HTML?
An HTML form is used to collect user input. The user input is most often sent to a server for processing. <br>
We will discuss some useful input types and tags related to forms.

### Structure of a `<form>` container
```html
<form>
.
.
form elements
.
.
</form>
```

The &lt;form&gt; element is a container for different types of input elements, such as text fields, checkboxes, radio buttons, submit buttons, etc.
<hr>

### The &lt;input&gt; element
The HTML &lt;input&gt; element is the most used form element.
```html
 <label for="fname">FIRST NAME :</label>
 <input type="text" name="fname" id="fname" placeholder="enter first name"/>
 <label for="lname">LAST NAME :</label>
 <input type="text" name="lname" id="lname" placeholder="enter last name"/>
```

Placeholder attribute used to show some translucent text which tells the user wants to input in this section.<br>
As per the above example `placeholder="enter first name"` says to the user enter here your first name.

### Types of &lt;input&gt;
```html
<input type="text"/>
```
Shows a single line 'text' input field
eg. Name, Father's Name, Mother's Name, etc.

```html    
<input type="number"/>
```
Shows a single line 'number' input field
eg. Phone Numbers

```html   
<input type="email"/>
```
Shows a single line 'email' input field
eg. email address

```html
<input type="radio"/>
```
Displays a radio button(to select one of many choices)
eg. gender, stream of study in college, etc.

```html
<input type="checkbox"/>
```
Displays a checkbox(to zero or more of many choices)
eg. food you want to eat

```html       
<input type="submit"/>
```
Shows a submit button(for submitting the form)

```html    
<input type="file"/>
```
Shows a option to add file(image/video/music)

```html
<button>Click me</button>
```
Displays a clickable button

### The &lt;label&gt; element
The &lt;label&gt; tag defines a label for many form elements. <br>
The &lt;label&gt; element is useful for screen-reader users.<br>
The &lt;label&gt; element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the &lt;label&gt; element, it toggles the radio button/checkbox. <br>

The 'for' attribute of the &lt;label&gt; tag should be equal to the id attribute of the &lt;input&gt; element to bind them together.
```html
 <label for="fname">FIRST NAME :</label>
 <input type="text" name="fname" id="fname" placeholder="enter first name"/>
 <label for="lname">LAST NAME :</label>
 <input type="text" name="lname" id="lname" placeholder="enter last name"/>
 <input type="radio" id="male"/>
 <label for="male">Male</label>
 <input type="radio" id="female"/>
 <label for="female">Female</label>
```

### The &lt;textarea&gt; element
Textarea tag used to display a multi-line text input, the size of columns and rows will be manipulate by CSS.
```html
 <textarea name="" id="" cols="120" rows="8"></textarea>
```

### The &lt;fieldset&gt; element and The &lt;legend&gt;
The &lt;fieldset&gt; tag is used to group related elements in a form. <br>
The &lt;fieldset&gt; tag draws a box around the related elements.

```html
<fieldset>
        <legend>GENDER</legend>
        <label> for="male">MALE</label>
        <input type="radio" name="gender" id="male" />

        <label> for="female">FEMALE</label>
        <input type="radio" name="gender" id="female" />
</fieldset>
```

> The &lt;legend&gt; tag defines a caption for the &lt;fieldset&gt; element.
