# Scraper example with nodeJS

## Installation
1. Download or clone the rep
2. Run `npm install`

## Using
1. Run `npm start`
2. Open your browser: http://localhost:8080/scraper
3. Go to your CLI and check ok message
4. A new file named `output.json` should be created in your project folder with this content
```
  {
      "title": "Machete (2010)",
      "release": "2010",
      "rating": "6.7"
  }
```

## A NOTE ON WEB SCRAPING
Web scraping falls within a gray area of the law. Scraping data for personal use within limits is generally ok but you should always get permission from the website owner before doing so. This example here is very minimalistic in a sense (one request to IMDB) so that it does not interfere with IMDB’s operations. <strong>Please scrape responsibly.</strong>

## Credits
Inspired on a [scotch.io tutorial](https://scotch.io/tutorials/scraping-the-web-with-node-js) by [Ado Kukic](https://github.com/kukicado)
