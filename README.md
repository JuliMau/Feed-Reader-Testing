# Feed-Reader-Testing
FEND4 Feed Reader Testing Project
# Project Overview

This is FEND Feed Reader Testing Project.
The project aims at writing a number of tests against a pre-existing
Feed Reader application by using behaviour-driven development
framework [Jasmine](http://jasmine.github.io/).

# Project Structure

The testing is conducted by writing specs containing suites against
blocks of application code. Upon running, the framework indicates the number of specs and
failures. The suites(headers) are marked in black colour, and specs are in green.
See picture: ![alt text](https://github.com/JuliMau/Feed-Reader-Testing/edit/master/feed_reader_test.jpg).


## What Have Been Tested

* Each feed is in a passing state, it has a name and it's URL defined
* The Menu becomes hidden and visible by clicking the menu icon
* When a feed is loaded, the .feed container has at least a single .entry
* When a new feed is loaded, the content also changes

### How
The tests have been written into **./jasmine/spec/feedreader.js** file.

# Where to Download

The application test can be run by downloading this project 
and running the file index.html on the browser.

## Resources
* [Jasmine](http://jasmine.github.io/)
* [Jasmine-jQuery](https://github.com/velesin/jasmine-jquery)
