# CHAPTER 8
## Table in HTML <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/htmlLogo.png" height="20px" />
![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML.png)

### What is a Table in HTML?
HTML tables are structured sets of data in rows and columns.<br>
They are created using the `<table>` tag and one or more &lt;tr&gt;, &lt;th&gt;, and &lt;td&gt; elements. <br>
Each table cell is defined by a &lt;td&gt; and a &lt;/td&gt; tag. The &lt;table&gt; tag includes global attributes that indicate how the table must be aligned inside the containing document. <br>
Tables are useful for presenting text information and numerical data, and for quickly and easily finding connections between different types of data. They are also used to create databases.

<pre>
&lttr&gt Used to display table row 
&lttd&gt Used to display table data
&ltth&gt Used to display table header
</pre>

### Table can be divided into parts
```
<thead>
       Used to deploy the header part of the table
</thead>
<tbody>
      Used to deploy information part of the table
</tbody>
```

```
<table>
      <thead>
        <tr>
          <th>Student Name</th>
          <th>Obtained Marks</th>
          <th>Result Status</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>Akash Sharma</td>
          <td>322</td>
          <td>1st Division</td>
        </tr>
        <tr>
          <td>Vijay Thakur</td>
          <td>298</td>
          <td>2nd Division</td>
        </tr>
        <tr>
          <td>Anand Kumar</td>
          <td>301</td>
          <td>1st Division</td>
        </tr>
      </tbody>
</table>
```
After creating a table We want to show a heading to describe the component of the table.

<pre>
&ltcaption&gt are used to show information like the heading of the table
</pre>

For expanding cells or merging cells we use
```
<table>
      <thead>
        <!-- colspan used to merge columns -->
        <tr>
          <th>Student Name</th>
          <th colspan="2">Result Status</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <!-- rowspan used to merge rows -->
          <td>Akash Sharma</td>
          <td>322</td>
          <td rowspan="2">1st Division</td>
        </tr>
        <tr>
          <td>Anand Kumar</td>
          <td>301</td>
        </tr>
      </tbody>
</table>
```

`<th rowspan="2">` -- for merging two cells in a row
`<th colspan="2">`-- for merging two cells in column
</pre>

**Note**: For better understanding, I used some simple CSS to make it clear in html file
