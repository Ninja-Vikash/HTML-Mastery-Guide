# CHAPTER 4
### Page layout techniques.

![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML.png)

**Layouting of tags**.
<ol>
<li>Tags are divided into two categories.</li>
<ul>
<li>Semantic tag</li>
<pre>
&ltheader&gt
&ltmain&gt
&ltfooter&gt
</pre>
and so on...

<li>Non-semantic tag</li>
<pre>
&ltspan&gt
&ltdiv&gt
&ltsection&gt
</pre>
</ul>
<li>Arrangement of Semantic tags-</li>
<pre>
&ltbody&gt
    &ltheader>&lt!--Heading of the page--&gt&lt/header&gt
    &ltmain>&lt!--Your content will be here--&gt&lt/main&gt
    &ltfooter>&lt!--Footer--&gt&lt/footer&gt
&lt/body&gt
</pre>

The Main is divided into more semantic tags. As below-

<pre>
&ltmain&gt
      &ltsection&gt
        &lth2&gtAbout&lt/h2&gt
        &ltp&gt
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam, saepe reprehenderit<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quia minima quoscommodi blanditiis illum est repudiandae possimus sit animi eum, delectus, asperiores dolorum<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;eligendi 
        &lt/p&gt
      &lt/section&gt

      &ltsection&gt
        &lth2&gtRead More&lt/h2&gt
        &ltp&gt
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam,<br> saepe reprehenderit quia minima quos            commodi blanditiis illum est repudiandae possimus<br> sit animi eum, delectus, asperiores dolorum eligendi 
        &lt/p&gt
      &lt/section&gt

      &ltsection&gt
        &lth2&gtContact&lt/h2&gt
        &ltp&gt
          Phone : +1234567890
          Email : abc@gmail.com
        &lt/p&gt
      &lt/section&gt

      &ltarticle&gt
        &lth4&gt
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam,<br> saepe reprehenderit quia minima                 quos commodi blanditiis illum est repudiandae possimus sit animi eum,<br> delectus, asperiores dolorum eligendi excepturi!                     Sapiente, facilis et?
        &lt/h4&gt
      &lt/article&gt

      &ltaside&gt
        &ltp&gt
            Product : cloth | Rs 499 <br>
            Product : shoes | Rs 799 <br>
            Product : Bags | Rs 399
        &lt/p&gt
      &lt/aside&gt
&lt/main&gt
</pre>
<br>

You can see an example of semantic layout--> portfolio.html
</ol>
