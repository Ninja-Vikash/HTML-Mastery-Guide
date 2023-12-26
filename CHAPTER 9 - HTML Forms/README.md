# CHAPTER 9
## Forms in HTML <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/htmlLogo.png" height="20px" />
![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML.png)

### What is form in HTML?
An HTML form is used to collect user input. The user input is most often sent to a server for processing. <br>
We will discuss some useful input types and tags related to forms.

### Structure of a 'Form' container
<pre>
&lt;form&gt;
        .
        .
        form elements
        .
        .
&lt;/form&gt;
</pre>
The &lt;form&gt; element is a container for different types of input elements, such as text fields, checkboxes, radio buttons, submit buttons, etc.
<hr>

### The &lt;input&gt; element
The HTML &lt;input&gt; element is the most used form element.
<pre>
        &ltlabel for="fname"&gtFIRST NAME :&lt/label&gt
        &ltinput type="text" name="fname" id="fname" placeholder="enter first name"&gt
        &ltlabel for="lname"&gtLAST NAME :&lt/label&gt
        &ltinput type="text" name="lname" id="lname" placeholder="enter last name"&gt
</pre>

Placeholder attribute used to show some translucent text which tells the user wants to input in this section.<br>
As per the above example placeholder="enter first name" says to the user enter here your first name.

### Types of &lt;input&gt;
<pre>
&lt;input type="text"&gt; - Shows a single line 'text' input field
eg. Name, Father's Name, Mother's Name, etc.
        
&lt;input type="number"&gt; - Shows a single line 'number' input field
eg. Phone Numbers
        
&lt;input type="email"&gt; - Shows a single line 'email' input field
eg. email address
        
&lt;input type="radio"&gt; - Displays a radio button(to select one of many choices)
eg. gender, stream of study in college, etc.
        
&lt;input type="checkbox"&gt; - Displays a checkbox(to zero or more of many choices)
eg. food you want to eat
        
&lt;input type="submit"&gt; - Shows a submit button(for submitting the form)
</pre>

<pre>
&lt;button&gt;Click me&lt;/button&gt; - Displays a clickable button
</pre>

### The &lt;label&gt; element
The &lt;label&gt; tag defines a label for many form elements. <br>
The &lt;label&gt; element is useful for screen-reader users.<br>
The &lt;label&gt; element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the &lt;label&gt; element, it toggles the radio button/checkbox. <br>

The 'for' attribute of the &lt;label&gt; tag should be equal to the id attribute of the &lt;input&gt;         element to bind them together.

