# CHAPTER 2
## Fundamentals of HTML <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/htmlLogo.png" height="20px" /> | HTML Entities

![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML.png)
### Information of HTML tags

1. **HTML is not case-sensitive**
<pre>
&lthtml&gt = &ltHTML&gt
&ltp&gt = &ltP&gt
&lthead&gt = &ltHEAD&gt
&ltbody&gt = &ltBODY&gt
</pre>

2. **What is an HTML element?**
   <p>An HTML element is defined by a &lt;start tag&gt;context&lt;end tag&gt;</p>
   
3. **Basic Tags-**
<p>For Simple content writing-</p>
<pre>&ltp&gt-----This is a paragraph tag----&lt/p&gt</pre>
<pre>&ltpre&gt---This is a pre tag---&lt/pre&gt</pre>

4. **For Headings-**
<pre>
&lth1&gtHeading 1&lt/h1&gt
&lth2&gtHeading 2&lt/h2&gt
&lth3&gtHeading 3&lt/h3&gt
&lth4&gtHeading 4&lt/h4&gt
&lth5&gtHeading 5&lt/h5&gt
&lth6&gtHeading 6&lt/h6&gt
</pre>
  
![Heading](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/Headings.png)

<p>When writing headings, the size of the text should decrease from h1 (the largest) to h6 (the smallest).</p>

5. **Text Formatting Tags-**
<pre>
&ltb&gtI am Bold&lt/b&gt                  
&lti&gtI am Italic&lt/i&gt                
&ltu&gtI am Underline&lt/u&gt 
</pre>
<p><b>I am Bold</b><br><i>I am Italic</i></p>
<p>💡<b>Tip:</b> &ltstrong&gt tag is similar to the &ltb&gt tag and &ltem&gt tag is similar to the &lti&gt tag</p>
<pre>
&ltbig&gtI am Big&lt/big&gt
&ltsmall&gtI am Small&lt/small&gt
</pre>

<pre>
&ltsup&gtI am Superscript&lt/sup&gt
&ltsub&gtI am Subscript&lt/sub&gt
</pre>
</ol>

### Notable 
Sometimes we use some special characters on a web page like angular brackets, copyright symbols, trademark symbols, etc. <br>
But there is a problem with HTML we can't use angular brackets directly because HTML takes them as a tag, if we use opening and closing angular brackets together it will affect our code. To solve this bug we will use **HTML Entity**
<br>It starts with Ampersand (&) and should be closed with a semi-colon (;), <br>

**List of HTML Entities**
<pre>
● Non-breaking spaces - &ampnbsp&semi;
● &copy; - Copyright - &ampcopy&semi;
● &amp; - Ampersand - &ampamp&semi;
● &semi; - SemiColon - &ampsemi&semi;
● &reg; - Registered - &ampreg&semi;
● &trade; - Trademark - &amptrade&semi;
● &commat; - At the rate - &ampcommat&semi;
● &star; - Holo Star - &ampstar&semi;
● &starf; - Filled Star - &ampstarf&semi;
● &phone; - Phone - &ampphone&semi;
● &male; - Male - &ampmale&semi;
● &female; - Female - &ampfemale&semi;
● &hearts; - Heart - &amphearts&semi;
● &spades; - Spade - &ampspades&semi;
● &clubs; - Club - &ampclubs&semi;
● &diams; - Diamond - &ampdiams&semi;
● &sung; - Tune - &ampsung&semi;
● &check; - Check - &ampcheck&semi;
</pre>

<p>There are so many symbols in HTML we can use them to add # after &</p>

<a href="https://github.com/Ninja-Vikash/HTML/tree/main/CHAPTER%203%20-%20Attributes">
   <img src="https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/next-removebg-preview.png" height="30px" />
</a>
