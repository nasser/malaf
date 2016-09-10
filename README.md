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

Will generate `README.md.pdf`. You can pass the path to a CSS file following the markdown file and it will be used to style the page, otherwise it will use the included `style.css`. It will also watch the file and update the PDF when it changes.

## License

Copyright © Ramsey Nasser 2015-2016. Provided under the [MIT License](http://opensource.org/licenses/MIT)