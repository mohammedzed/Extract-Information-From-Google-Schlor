
Rerunning the Scraper
---------------------

Assuming you have [node.js](http://nodejs.org/) installed, rerun the scraper as follows:

```
$ npm install request cheerio async
$ node scrape.js ./people-hci.json > stats-hci.js
```

To scrape the images:

```
$ node download-images.js ./stats-hci.js
```

Then open up `index.html` and it should display the new statistics.
