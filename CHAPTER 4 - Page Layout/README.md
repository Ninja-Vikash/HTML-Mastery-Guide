# CHAPTER : 4

### Page layout techniques.

Layouting of tags.

<hr>
1. Tags are divided into two categories.
<br>
(A) Semantic tag
<pre>
&ltheader&gt
&ltmain&gt
&ltfooter&gt
</pre>
and so on...

(B) Non-semantic tag

<pre>
&ltspan&gt
&ltdiv&gt
&ltsection&gt
</pre>

Arrangement of Semantic tags-

<pre>
&ltbody&gt
    &ltheader>&lt!--Heading of the page--&gt&lt/header&gt
    &ltmain>&lt!--Your content will be here--&gt&lt/main&gt
    &ltfooter>&lt!--Footer--&gt&lt/footer&gt
&lt/body&gt
</pre>

Main is divided into more semantic tags. As below-

<pre>
&ltmain&gt
      &ltsection&gt
        &lth2>About</h2&gt
        &ltp&gt
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam, saepe reprehenderit quia minima quos commodi blanditiis illum est repudiandae possimus sit animi eum, delectus, asperiores dolorum eligendi 
        &lt/p&gt
      &lt/section&gt

      &ltsection&gt
        &lth2>Read More</h2&gt
        &ltp&gt
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam, saepe reprehenderit quia minima quos commodi blanditiis illum est repudiandae possimus sit animi eum, delectus, asperiores dolorum eligendi 
        &lt/p&gt
      &lt/section&gt

      &ltsection&gt
        &lth2>Contact</h2&gt
        &ltp&gt
          Phone : +1234567890 <br>
          Email : abc@gmail.com
        &lt/p&gt
      &lt/section&gt

      &ltarticle&gt
        &lth4&gt
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam, saepe reprehenderit quia minima quos commodi blanditiis illum est repudiandae possimus sit animi eum, delectus, asperiores dolorum eligendi excepturi! Sapiente, facilis et?
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

You can see a example of semantic layout--> portfolio.html