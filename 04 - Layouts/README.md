##### HTML Mastery Guide

# Layout of any HTML Document

### Why layout plays a vital role in a HTML document?
Layoutting HTML document is a good practice. Also it makes HTML document more readable during development. 

And browser easily identify, What kind of data is stored inside any section.

There are two major techniques for layoutting any HTML document. By using:
1. **Semantic tags**

```html
<body>
    <header>
        <h1>Heading</h1>
        <nav>...</nav>
    </haeder>

    <main>
        <section>...</section>
        <section>...</section>
        <aside>...</aside>
    </main>

    <footer>
        <p>All the copyright&copy; reserved</p>
    </footer>
</body>
```
and so on...

2. **Non-semantic tags**
```html
<body>
    <div class="header">
        <h1>Heading</h1>
        <nav>...</nav>
    </div>

    <div class="main">
        <section>...</section>
        <section>...</section>
        <aside>...</aside>
    </div>

    <div class="footer">
        <p>All the copyright&copy; reserved</p>
    </div>
</body>
```
> [!NOTE]\
> In `non-semantic` tag arrangement we use classes or ids for easy identification.\
> While `semantic` tags are automatically identified by their names.

***
### Distribution of tags
`main` tag is further distributed in multiple tags as:

```html
<main>
      <section>
        <h2>About</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam, saepe reprehenderitquia minima quoscommodiblanditiis illum est repudiandae possimus sit animi eum, delectus, asperiores dolorum eligendi 
        </p>
      </section>

      <section>
        <h2>Read More</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam, saepe reprehenderitquia minima quoscommodiblanditiis illum est repudiandae possimus sit animi eum, delectus, asperiores dolorum eligendi 
        </p>
      </section>

      <section>
        <h2>Contact</h2>
        <p>
          Phone : +1234567890
          Email : abc@gmail.com
        </p>
      </section>

      <article>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam corrupti suscipit aperiam, saepe reprehenderitquia minima quoscommodiblanditiis illum est repudiandae possimus sit animi eum, delectus, asperiores dolorum eligendi 
        </p>
      </article>

      <aside>
        <p>
            Product : cloth | Rs 499 <br>
            Product : shoes | Rs 799 <br>
            Product : Bags | Rs 399
        </p>
      </aside>
</main>
```

**Look**

Here is a [demo.html](demo.html)

#### Happy coding! 🤝

