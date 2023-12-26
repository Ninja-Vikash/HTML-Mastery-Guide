# CHAPTER 7
## Lists in HTML <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/htmlLogo.png" height="20px" />
![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML.png)

### What are lists in HTML?
A list in HTML is a collection of items that are displayed in a list format with bullet points. Lists are used to represent real-life data. There are three list types in HTML, each with a specific purpose and tag.
1. **Ordered List** &nbsp; 2. **Unordered List** &nbsp; 3. **Description List**

### Ordered List
An **unordered list**, also known as a bulleted list, has no specific order or sequence and is marked with bullets. It begins with the &lt;ul&gt; tag and closes with a &lt;/ul&gt; tag, while the list items begin with the &lt;li&gt; tag and end with &lt;/li&gt; tag. An **unordered list** is ideal for presenting a glossary, list of terms, or other name/value list.

<pre>
                                      Ordered List &ltol&gt

                                &ltol&gt
                                    &ltli&gtFirst Item&lt/li&gt
                                    &ltli&gtSecond Item&lt/li&gt
                                    &ltli&gtThird Item&lt/li&gt
                                    &ltli&gtFourth Item&lt/li&gt
                                &lt/ol&gt

1. First Item                       a. First Item                      I. First Item
2. Second Item                      b. Second Item                     II. Second Item
3. Third Item                       c. Third Item                      III. Third Item
4. Fourth Item                      d. Fourth Item                     IV. Fourth Item
</pre>
we can change the list style type by using CSS property. - Numbers, Alphabets(small & caps), Roman(small & caps).

2. Unordered List
<pre>
                                       Unordered List &ltul&gt
                                
                                &ltul&gt
                                    &ltli&gtFirst Item&lt/li&gt
                                    &ltli&gtSecond Item&lt/li&gt
                                    &ltli&gtThird Item&lt/li&gt
                                    &ltli&gtFourth Item&lt/li&gt
                                &lt/ul&gt
</pre>
we can change the list style type by using CSS property. - Bullet, Circle, Disk, Square.

3. Descripted List
<pre>
&ltdl&gt
      &ltdt&gtHow to make : Tea&lt/dt&gt
      &ltdd&gtTake a small container that is used to make tea.&lt/dd&gt
      &ltdd&gt
        Consume a limited amount of water according to how many people want to
        take the tea. suppose 3 people
      &lt/dd&gt
      &ltdd&gtFor 3 people we need to use 1 litre of water.&lt/dd&gt
      &ltdd&gtuse 2 full spoon tea leaf.&lt/dd&gt
      &ltdd&gtuse 2+1/2 spoon sugar.&lt/dd&gt
      &ltdd&gtBoil it at least 12 minutes.&lt/dd&gt
      &ltdt&gtHow to make : maggie&lt/dt&gt
      &ltdd&gtLorem ipsum dolor sit amet consectetur adipisicing.&lt/dd&gt
      &ltdd&gtLorem ipsum dolor sit amet.&lt/dd&gt
      &ltdd&gtLorem ipsum dolor sit amet consectetur.&lt/dd&gt
      &ltdd&gtLorem ipsum dolor sit amet consectetur adipisicing.&lt/dd&gt
    &lt/dl&gt
</pre>
This is a rarely used list type and is used for informative lists. <br>

**Note** : For the list Border style We need to check out CSS.
