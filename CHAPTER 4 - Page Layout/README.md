# CHAPTER 4
## 🔴 Page layout techniques <img src="https://github.com/Ninja-Vikash/asset-cloud/blob/main/icon%20%26%20png/htmlLogo.png" height="20px" />

![Banner](https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/HTML.png)

### Arrangement of tags in an HTML document

Tags are divided into two categories <br>
- **Semantic tag**
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

- **Non-semantic tag**
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


The `<main>` is divided into several semantic tags. As follow-

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
<br>

You can see an example of semantic layout--> <a href="https://github.com/Ninja-Vikash/HTML/blob/main/CHAPTER%204%20-%20Page%20Layout/portfolio.html">*demo.html*</a>
</ol>

<a href="https://github.com/Ninja-Vikash/HTML/tree/main/CHAPTER%205%20-%20Anchor%20Tag">
    <img src="https://github.com/Ninja-Vikash/asset-cloud/blob/main/assets%20-%20HTML/next-removebg-preview.png" height="30px" />
</a>
