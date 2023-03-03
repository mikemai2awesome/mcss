# The MCSS
A SuperMinimalCSS framework inspired by the typefaces of Matthew Carter.

## Typography
MCSS is a tribute to the British type designer Matthew Carter. The framework is designed with two of Carter’s most commonly known typefaces—Georgia and Verdana. The New Yorker once described Carter as "the most widely read man in the world" as his typefaces are available as system fonts in most operating systems.

## Accessibility
MCSS works with good old semantic HTML. It is accessible by default.

### Page sctructure
MCSS is designed for writing articles. To create a standard page as the one you are reading now, use the following semantic HTML template.

```html
<header>
  <h1>Page Title</h1>
  <p>Page description.</p>
</header>
<hr>
<main>
  <section>
    <h2>Section Title</h2>
    <p>Section content.</p>
  </section>
  <section>
    <h2>Section Title</h2>
    <p>Section content.</p>
  </section>
</main>
<hr>
<footer>
  <p>Footer content</p>
</footer>
```

### Perfect for writing with Markdown
Set up the page template with your blog and use the <main> container as the article body. Markdown renders semantic HTML so everything will just work.

```html
<header>
  <h1>{{ title }}</h1>
  <p>{{ description }}</p>
</header>
<hr>
<main>
  <!-- Markdown goes here --!>
</main>
<hr>
<footer>
  {{ footer }}
</footer>
```
