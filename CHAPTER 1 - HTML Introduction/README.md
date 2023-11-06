# CHAPTER 1

### INTRODUCTION OF HTML

![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML%20introduction.png)
<b>HTML</b> : Hypertext Markup Language<br>
HTML is the code that is used to structure a web page and its content. And the components used to design the structure of websites are called HTML tags. It is often assisted by technologies such as Cascading Style Sheets and Scripting languages such as Javascript.

<hr>
1. How to create an HTML document. <br>
   Using the below syntax-
<pre>
&lt!DOCTYPE html&gt
&lthtml lang="en"&gt
  &lthead&gt
    &ltmeta charset="UTF-8" /&gt
    &ltmeta name="viewport" content="width=device-width, initial-scale=1.0" /&gt
    &lttitle&gtDocument&lt/title&gt
  &lt/head&gt
  &ltbody&gt
      ------Your code will be here!------
  &lt/body&gt
&lt/html&gt
</pre>
The above code is called the <b>Boiler Plate</b>. <br>
We can write it with the emmet abbreviation <b>!</b> + <b>enter</b> | <b>html5</b> + <b>enter</b> <br>
Both methods are useful for deploying boilerplate.
<br>
2. All the elements within angular barckets <> called as <b>Tags</b>
most of the element are closed with two tags like <u>opening tag</u> &lttag&gt context &lt/tag&gt <u>closing tag</u> <br>
But there are a few tags that are self-closed tag: <br>
Example : <p>&ltbr&gt , &lthr&gt , &ltimg&gt and so on..</p>
3. Overview of Boilerplate-
<pre>
&lt!DOCTYPE html&gt
</pre>
&lt!DOCTYPE html&gt tells the browser this document is a HTML document.

<pre>
&lthtml&gt
  -------Everything inside the html tag is the part of HTML--------
&lt/html&gt  
</pre>
&ltHTML&gt is the parent container.
<pre>
&lthead&gt
  -------Contains the meta data, title, link and other useful tags which is not render on browser's screen--------
&lt/head&gt

&ltbody&gt
  -------Contains the main data and reflect to the browser's screen--------
&lt/body&gt
</pre>
&lthead&gt and &ltbody&gt are children tags of HTML tag.
<pre>
&ltmeta  -------useful data------  &gt
</pre>
&ltmeta&gt is self closed tag which stores useful data like character used in document, content-width, initial-scale for different size screen.<br>
&ltmeta&gt contains special information about the webpage. These are generally for browsers to use.
<pre>
&lttitle&gt-----Name of the Webpage-----&lt/title&gt
</pre>
&lttitle&gt is used to give name to the Webpage, When we search through the Internet. It shown on the browser's tab bar.
<pre>
&ltbody&gt
  --------All the data which is reflected on browser's screen---------
&lt/body&gt
</pre>
&ltbody&gt is also a container used to add data which is reflected on browser's main screen. <br>
4. Comments are written as
<pre>
&lt!-- Your comment is here --&gt
</pre>
