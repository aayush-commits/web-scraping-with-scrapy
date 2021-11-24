# web-scraping-with-scrapy
Simple python program to scrape data from Stack Overflow.

## Getting Started

### Dependencies
* Scrapy

### Executing program

* `cd` into the repo
* Run with
```
scrapy crawl stack -o items.json -t json
```
You should see 50 questions titles and URLs stored in a json file.
