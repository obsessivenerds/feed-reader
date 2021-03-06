# Feed Reader Testing Project

The goal of this project is to successfully complete the test suite for a web-based feed reader application using [Jasmine](http://jasmine.github.io/).


## Dependencies

This code is dependent upon:

* Jasmine - https://jasmine.github.io/2.9/introduction
* Google Fonts - Roboto font family
* jQuery
* Handlebars


## Instructions

To run the program simply download or clone the files, then load the index.html file in your browser of choice. You will see the series of tests at the bottom of the page.


## Included Tests

The following tests are included in the program:

* Make sure that the allFeeds variable has been defined and that it is not empty.
* Loops through each feed in the allFeeds object and ensure it has a URL defined and that the URL is not empty.
* Loop through each feed in the allFeeds object and ensure it has a name defined and that the name is not empty.
* Ensure the menu element is hidden by default.
* Ensure the menu changes visibility when the menu icon is clicked.
* Ensure when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
* Ensure when a new feed is loaded by the loadFeed function that the content actually changes.
