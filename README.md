
# webcrawler_template

## requirements

- [X] based on scrapy.
- [ ] support POST method.
    - that does not require parameter analysis.
    - by using headless browser.
- [ ] separate crawler and scraper functions in a spider.
    - crawler function controls how a spider traverse a web site.
    - scraper function controls how a spider scrape a web page.
- [ ] unit tests as requirement description for crawler and scraper functions.
- [ ] spider outputs items incrementally.
    - into object storage
    - with compression

## reference

- [scrapy](https://scrapy.org/)
- [scrapy-plugins/scrapy-splash](https://github.com/scrapy-plugins/scrapy-splash)
