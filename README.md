# html_partial
Micro Tiny HTML Partial View Manager

This simple Pure Javascript client-side Partial View manager will check for all partial tags and replace it with the HTML content from its src attribute.

How to do?

1. Just add the reference to the script html_partial.js in your index.html file.
2. Add partial tags where you want to include html from external file.

  ```html
  <!doctype html>
  <html lang="en">
  <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
  <body>
      <div>
          <partial src="/parts/top_header.html" /> 
      </div>
      <script src="lib/html_partial.js"></script>
  </body>
  </html>
  ```
