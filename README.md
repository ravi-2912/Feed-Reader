# RSS Feed Reader with Tests

This is a web-based application that reads RSS feeds. the primary aim of this project is to demonstrate testing using [Jasmine](http://jasmine.github.io/). Feeds are gathered from the following locations:

* [Udacity Blog](http://blog.udacity.com/feed)
* [CSS Tricks](http://feeds.feedburner.com/CssTricks)
* [HTML5 Rocks](http://feeds.feedburner.com/html5rocks)
* [Linear Digressions](http://feeds.feedburner.com/udacity-linear-digressions)


## Running the application
Download the repository and run `index.html`.
### Dependencies
[Jasmine](http://jasmine.github.io/) ver. 2.1.2 is needed to run the tests. Jasmine version is provided in the source.


## Tests
The following tests are implemented:

1. A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. A test that ensures the menu element is hidden by default. 
4. A test that ensures the menu changes visibility when the menu icon is clicked.
5. A test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
6. A test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
