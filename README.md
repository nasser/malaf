# Malaf
Markdown + CSS -> PDFs

## Usage

First install [wkhtmltopdf](http://wkhtmltopdf.org/downloads.html). Then

```
node malaf.js foo.md
```

Will generate `foo.md.pdf`. If a `style.css` is in the same directory it, will be used to style the page. It will also watch the file and update the PDF when it changes.

## Future

* Multiple files
* Multiple stylesheets
* Configuration
* Code Highlighting
* MathJax

## License

Copyright © Ramsey Nasser 2015. Provided under the [MIT License](http://opensource.org/licenses/MIT)