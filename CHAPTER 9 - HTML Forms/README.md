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

### &lt;input&gt; elements
The HTML <input> element is the most used form element.
<pre>
        &ltlabel for="fname"&gtFIRST NAME :&lt/label&gt
        &ltinput type="text" name="fname" id="fname" placeholder="enter first name"&gt
        &ltlabel for="lname"&gtLAST NAME :&lt/label&gt
        &ltinput type="text" name="lname" id="lname" placeholder="enter last name"&gt
</pre>

Placeholder attribute used to show some translucent text which tells the user wants to input in this section.<br>
As per the above example placeholder="enter first name" says to the user enter here your first name.<br>
There are so many **input types** used in HTML forms.

<pre>
&ltinput type="text"&gt for Text Information Adding in form.<br>eg. Name, Father's Name, Mother's Name etc.
&ltinput type="number"&gt for Number Information Adding in form.<br>
eg. Phone Numbers
&ltinput type="email"&gt for Email of the user Adding in form.<br>
eg. email address
&ltinput type="radio"&gt for choose one option from them.<br>
eg. Gender, stream of study in college, etc.
&ltinput type="checkbox"&gt fot selecting multiple options.
&ltinput type="submit" value="submit"&gt for submitting data to server.
</pre>

<pre>
&ltbutton&gtClick&lt/button&gt used to create buttons for user interaction.
</pre>

