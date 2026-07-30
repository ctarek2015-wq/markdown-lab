# How to write an HTML Boilerplate

![html](https://images.unsplash.com/photo-1746292183139-140988de7b90?q=80&w=873&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
To write a standard _HTML5 boilerplate_, you create a file (typically named index.html) containing the fundamental structure required for modern web development.

This structure includes:

- the document type declaration.
- language attributes.
- metadata for character encoding and responsive design.
- placeholders for your content and scripts.

## Basic HTML5 Boilerplate Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>My Website</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="icon" href="favicon.ico" type="image/x-icon" />
  </head>
  <body>
    <main>
      <h1>Welcome to My Website</h1>
    </main>
    <script src="index.js"></script>
  </body>
</html>
```

Key Components Explained

**DOCTYPE Declaration**: `<!DOCTYPE html>` tells the browser to render the page as HTML5. Without this, modern semantic tags like `<article>` or `<section>` may not render correctly.

**Root Element**: The `<html lang="en">` tag defines the root of the document and the language of the content, which is critical for accessibility (screen readers) and SEO.

**Head Section**: Contains metadata invisible to users but essential for browsers and search engines:

- `<meta charset="UTF-8">`: Sets the character encoding to UTF-8, supporting most languages and special characters.
- `<meta name="viewport" ...>`: Ensures responsive design by setting the page width to the device's screen width and preventing default zoom.
- `<title>`: Sets the text displayed in the browser tab and search engine results.
- `<link>`: Used to connect external CSS stylesheets and favicons.
  Body Section: Contains the visible content of the website.
- `<main>`: A semantic tag indicating the primary content of the document.
- `<script>`: External JavaScript files are typically linked here, just before the closing `</body>` tag, to improve page load performance.
  Shortcut in VS Code

#

### If you are using Visual Studio Code, you can generate this boilerplate instantly using Emmet:

1. Create a new file and save it with an .html extension.
2. Type ! or html:5 in the editor.
3. Press Tab or Enter.

This will automatically expand into the basic **_HTML5_** structure, saving you from typing the tags manually.
