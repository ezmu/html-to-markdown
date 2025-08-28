# HTML to Markdown Converter

A simple **HTML to Markdown** converter with support for selecting a specific element from any webpage. Built with JavaScript and [Turndown](https://github.com/domchristie/turndown).

---

## Features

- Convert full HTML or a specific element (via CSS selector) to Markdown.
- Live preview of the Markdown output.
- Supports images, links, lists, headings.
- Download the Markdown file directly.
- Works via a CORS proxy to fetch external webpages.

---

## Usage

You can open the converter directly from this repository:

[Open HTML to Markdown Converter](https://ezmu.github.io/html-to-markdown/index.html)

### Steps:

1. Enter a webpage URL.
2. Specify a CSS selector for the element you want to convert (e.g., `#content` or `.article`).
3. Click **Fetch & Convert**.
4. Or paste HTML manually into the textarea.
5. View the Markdown output and download it as `output.md`.

---

## Example

```html
# Enter the URL: https://example.com
# CSS Selector: #main-article
```

The converter will fetch the element with `id="main-article"` and generate Markdown.

---

## Notes

- Uses [AllOrigins CORS Proxy](https://allorigins.win/) to bypass cross-origin restrictions.
- Works best when opened in a modern browser.

---
**EzEldeen A. Y. Mushtaha**  
Senior Software Engineer | Problem-Solving Expert  
Email: 3z.eldeen@gmail.com  
[LinkedIn](https://www.linkedin.com/in/ezmush/)  
[GitHub Profile](https://github.com/ezmu)

## License

MIT License


