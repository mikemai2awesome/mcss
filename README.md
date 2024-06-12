# The MCSS
A modern classless CSS framework inspired by the typefaces of Matthew Carter.

## Typography
MCSS is a tribute to the British type designer Matthew Carter. The framework is designed with two of Carter’s most commonly known typefaces—Georgia and Verdana. The New Yorker once described Carter as “the most widely read man in the world” because his typefaces are available as system fonts in most operating systems.

## Theming
MCSS is available in two typographically different themes.

1. Georgia on my mind: Typeset primarily using Georgia with generous spacing.

   ```html
   <html data-theme="georgia">...</html>
   ```

2. Verdana mania: Typeset primarily using Verdana with compact spacing.

   ```html
   <html data-theme="verdana">...</html>
   ```

## Elements
With MCSS, some of the most common HTML elements are styled and can be used without any classes.

* `p`
* `q`
* `dl`
* `ol`
* `ul`
* `li`
* `nav`
* `footer`
* `header`
* `section`
* `caption`
* `h1` ~ `h6`
* `blockquote`
* `figcaption`
* `fieldset`
* `textarea`
* `details`
* `summary`
* `strong`
* `button`
* `figure`
* `select`
* `input`
* `label`
* `small`
* `table`
* `abbr`
* `code`
* `form`
* `sup`
* `sub`
* `kbd`
* `pre`
* `em`
* `hr`
* `a`

## Accessibility
MCSS is written for plain HTML. It is accessible by default.

### Best with semantic HTML
MCSS is designed for writing articles. To create a standard page, use the following semantic HTML template.

```html
<header>
  <h1>Page Title</h1>
  <p>Page description.</p>
  <nav>
    <ul role="list">
      <li>
        <a href="...">Link</a>
      </li>
      ...
    </ul>
  </nav>
</header>
<hr>
<main>
  <article>
    <section>
      <h2>Section Title</h2>
      <p>Section content.</p>
    </section>
    <section>
      <h2>Section Title</h2>
      <p>Section content.</p>
    </section>
  </article>
</main>
<hr>
<footer>
  <p>Footer content</p>
</footer>
```

### Perfect for writing with Markdown
Set up the page template with your blog and use the `<main>` `<article>` container as the article body. Markdown renders semantic HTML so everything will just work.

```html
<header>
  <h1>{{ title }}</h1>
  <p>{{ description }}</p>
  <nav>
    <ul role="list">
      <li>
        <a href="{{ url }}">{{ link }}</a>
      </li>
      ...
    </ul>
  </nav>
</header>
<hr>
<main>
  <article>
    <!-- Markdown -->
    {{ content }}
    <!-- Markdown -->
  </article>
</main>
<hr>
<footer>
  Written by {{ author }} on {{ date }}.
</footer>
```

## Dark mode
MCSS auto-detects your operating system’s settings. Dark design is displayed if dark mode is your preferred setting. All colors—except Crimson—are defined by the browser. The black background in dark mode could appear slightly different from browser to browser.

## Notes
1. MCSS is a variant of Super­Minimal­CSS crafted by Mike Mai.
2. Georgia and Verdana might not be available in certain Android devices and device specific system fonts would render instead. Custom @font-face and web font licences are required to ensure Georgia and Verdana display in all devices.





