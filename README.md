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

## About Scrapy

* Scrapy is an application framework for crawling web sites and extracting structured data which can be used for a wide range of useful applications, like data mining, information processing or historical archival.

* Spiders are classes which define how a certain site (or a group of sites) will be scraped, including how to perform the crawl (i.e. follow links) and how to extract structured data from their pages (i.e. scraping items). In other words, Spiders are the place where you define the custom behaviour for crawling and parsing pages for a particular site (or, in some cases, a group of sites).

* `items.py` file contains the items you want to scrape from the page.

* 
