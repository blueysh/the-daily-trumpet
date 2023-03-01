# add your article!!

okay, to start, make a copy of the [`ARTICLE_TEMPLATE.html`](https://github.com/blueysh/the-daily-trumpet/tree/main/ARTICLE_TEMPLATE.html) file, rename it to the name of your article with `-` instead of spaces. in that template, everything you need to change is marked.

to make your article "breaking news", uncomment the line above the header that has the breaking news line on it.

to make your article show on the main page, copy the following snippet under the comment in [`index.html`](https://github.com/blueysh/the-daily-trumpet/tree/main/index.html) that says to copy your article under it.

```html
<div class="postcard">
  <span>
	  <h3>Your Article Name Goes Here</h3>
  </span>
  <h4>Published (Add Date Here) | <a href="your-article-name.html" class="navitem">Read Article</a></h4>
</div>
```

if your article is breaking news add this above the article name again

```html
	  <h3 class="standout">Breaking News</h3>
```