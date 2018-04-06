# FeedReader testing project

This is FEND Fead Reader where I used Jasmine to validate my code. I started with a Feed Reader App and was required to write test specs in Jasmine.


## How to run the application

Download the app from github.

To start the app, open index.html in your favourite browser.

The tests were written in the feedreader.js file. The test results appears at the bottom of the page.

Tests that are green have passed and red have failed.

## Tests used in this project

* tests to make sure that the allFeeds variable has been defined and it is not empty.
* test that loops through each feed and determines if the URL is defined and not empty.
* test that loops through each feed and determines that each feed has a name and name is not empty.
* test that ensures the menu element is hidden by default.
* test that validates proper functioning of the menu.
* tests to verify that there is at least one entry in feed.
* tests to verify that new content is loaded by loadFeed() function.