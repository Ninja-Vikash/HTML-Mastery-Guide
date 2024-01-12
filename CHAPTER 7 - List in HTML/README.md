# CHAPTER 7
## Lists in HTML <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/htmlLogo.png" height="20px" />
![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML.png)

### What are lists in HTML?
A list in HTML is a collection of items that are displayed in a list format with bullet points. Lists are used to represent real-life data. There are three list types in HTML, each with a specific purpose and tag.
1. **Ordered List** &nbsp; 2. **Unordered List** &nbsp; 3. **Description List**

### Ordered List
An **Ordered list**, also known as a step-by-step list, has a specific order or sequence and is marked with numbers. It begins with the &lt;ol&gt; tag and closes with a &lt;/ol&gt; tag, while the list items begin with the &lt;li&gt; tag and end with &lt;/li&gt; tag. An **Ordered list** is ideal for presenting a recipe, a to-do list, or any process.

<pre>
                                      Ordered List &lt;ol&gt;

                                &lt;ol&gt;
                                    &lt;li&gt;First Item&lt;/li&gt;
                                    &lt;li&gt;Second Item&lt;/li&gt;
                                    &lt;li&gt;Third Item&lt;/li&gt;
                                    &lt;li&gt;Fourth Item&lt;/li&gt;
                                &lt;/ol&gt;

1. First Item                       a. First Item                      I. First Item
2. Second Item                      b. Second Item                     II. Second Item
3. Third Item                       c. Third Item                      III. Third Item
4. Fourth Item                      d. Fourth Item                     IV. Fourth Item
</pre>
> we can change the list style type by using CSS property. - Numbers, Alphabets(small & caps), Roman(small & caps).

### Unordered List
An **unordered list**, also known as a bulleted list, has no specific order or sequence and is marked with bullets. It begins with the &lt;ul&gt; tag and closes with a &lt;/ul&gt; tag, while the list items begin with the &lt;li&gt; tag and end with &lt;/li&gt; tag. An **unordered list** is ideal for presenting a glossary, list of terms, or other name/value list.
<pre>
                                       Unordered List &lt;ul&gt;
                                
                                &lt;ul&gt;
                                    &lt;li&gt;First Item&lt;/li&gt;
                                    &lt;li&gt;Second Item&lt;/li&gt;
                                    &lt;li&gt;Third Item&lt;/li&gt;
                                    &lt;li&gt;Fourth Item&lt;/li&gt;
                                &lt;/ul&gt;
</pre>
> we can change the list style type by using CSS property. - Bullet, Circle, Disk, Square.

### Description List
HTML also supports description lists.
A description list is a list of terms, with a description of each term.
The &lt;dl&gt; tag defines the description list, the &lt;dt&gt; tag defines the term (name), and the &lt;dd&gt; tag describes each term

<pre>
&lt;dl&gt;
      &lt;dt&gt;How to make : Tea&lt;/dt&gt;
      &lt;dd&gt;Take a small container that is used to make tea.&lt;/dd&gt;
      &lt;dd&gt;
        Consume a limited amount of water according to how many people want to
        take the tea. suppose 3 people
      &lt;/dd&gt;
      &lt;dd&gt;For 3 people we need to use 1 litre of water.&lt;/dd&gt;
      &lt;dd&gt;use 2 full spoon tea leaf.&lt;/dd&gt;
      &lt;ldd&gt;use 2+1/2 spoon sugar.&lt;/dd&gt;
      &lt;dd&gt;Boil it at least 12 minutes.&lt;/dd&gt;
      &lt;dt&gt;How to make : maggie&lt;/dt&gt;
      &lt;dd&gt;Lorem ipsum dolor sit amet consectetur adipisicing.&lt;/dd&gt;
      &lt;dd&gt;Lorem ipsum dolor sit amet.&lt;/dd&gt;
      &lt;dd&gt;Lorem ipsum dolor sit amet consectetur.&lt;/dd&gt;
      &lt;dd&gt;Lorem ipsum dolor sit amet consectetur adipisicing.&lt;/dd&gt;
    &lt;/dl&gt;
</pre>
> This is a rarely used list type and is used for informative lists. <br>

**Note** : For the list Border style We need to check out CSS.
