# **Udacity Project: Feed Reader Testing**

### by Chris Corkhill

Description: Using Jasmine to write tests for a given web-based application that reads RSS feeds.


1. Consturcted tests that loops through each feed in the `allFeeds` object and ensures it has a URL and name are defined and that the URL and name are not empty.

2. Constructed a test suite named '"The menu"
	* Ensures the menu element is hidden by default.
	* Ensures the menu changes visibility when the menu icon is clicked.

3. Constructed a test suite named `"Initial Entries"'
	* Ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

4. Consturcted a test suite named `"New Feed Selection"`
	* Ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.


### Instructions:

1. Open the index file in the folder called 'frontend-nanodegree-feedreader-master' using Google Chrome Web Browser.
2. Scrolled down to the bottom to see the test completed and the results by the jasmine tests from `jasmine/spec/feedreader.js` 

### Resources:

[Jasmine](http://jasmine.github.io/) documentation

Udacity Javascript Testing Course

And of course *stackoverflow* and udacity forums
