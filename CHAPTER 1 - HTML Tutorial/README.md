# CHAPTER 1
### INTRODUCTION OF HTML

![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML%20introduction.png)
<b>HTML</b> : Hypertext Markup Language<br>
HTML is the code that is used to structure a web page and its content. And the components used to design the structure of websites are called HTML tags.
<hr>
1. How to create an HTML document. <br>
   Using the below syntax-
<pre>
&lt!DOCTYPE html&gt
&lthtml lang="en"&gt
  &lthead&gt
    &ltmeta charset="UTF-8" /&gt
    &ltmeta name="viewport" content="width=device-width, initial-scale=1.0" /&gt
    &lttitle>Document&lt/title&gt
  &lt/head&gt
  &ltbody&gt &lt/body&gt
&lt/html&gt
</pre>
The above code is called the <b>Boiler Plate</b>. <br>
We can write it with the emmet abbreviation <b>!</b> + <b>enter</b> | <b>html5</b> + <b>enter</b> <br>
Both methods are useful for deploying boilerplate.
<br>
2. All the elements within <> called as <b>TAGS</b>
most of the element are closed with two tags like <u>opening tag</u> context <u>closing tag</u> <br>
But there are a few tags that are self-closed tag: <br>
Example : <p>&ltbr&gt , &lthr&gt , &ltimg&gt and so on..</p>
3. Overview of Boilerplate-
<pre>
&lthtml&gt  &lt/html&gt  
</pre>
is a Parent container.
<pre>
&lthead&gt  &lt/head&gt <br>
&ltbody&gt  &lt/body&gt
</pre>
are children of HTML Tag.
<pre>
&ltmeta&gt
</pre>
contains special information about the webpage.
These are generally for browsers to use.
also, these are self-closing tags.
<pre>
&lttitle&gt
</pre>
used to name of page shown on the Browser tab bar.
<pre>
&ltbody&gt
</pre>
is also a container that the user uses to fetch data which is reflected on Browser's main screen. <br>
4. Comments are written as
<pre>
&lt!-- COMMENT --&gt
</pre>
