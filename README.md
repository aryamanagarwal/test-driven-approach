# About
This is a web-based application that reads RSS feeds.The application has been implemented using test driven approach.
Jasmine library has been used to implement test-driven development.

# How to run
Open index.html

# Some siginificant tests
1. loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. Loop through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. Test that ensures the menu element is hidden by default.
4. Test that ensures the menu changes visibility when the menu icon is clicked.
5.  Test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
6. Test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
