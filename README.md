# Malaf
Markdown + CSS = PDF

## Usage

First install [wkhtmltopdf](http://wkhtmltopdf.org/downloads.html). Then

```
git clone https://github.com/nasser/malaf.git
cd malaf
npm install
node malaf.js README.md
```

Will generate `README.md.pdf`. If a `style.css` is in the same directory it, will be used to style the page. It will also watch the file and update the PDF when it changes.

## License

Copyright © Ramsey Nasser 2015. Provided under the [MIT License](http://opensource.org/licenses/MIT)