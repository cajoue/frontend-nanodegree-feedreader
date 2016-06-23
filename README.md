# frontend-nanodegree-feedreader
Project is part of the [Udacity Front-End Web Developer Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001)

## Project Overview
In this project I was given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. 

## Project Objectives
To write a complete test suite using Jasmine to ensure the following:

[x] each feed in the allFeeds object has a URL defined and the URL is not empty

[x] each feed in the allFeeds object has a name defined and the name is not empty

[x] the menu element is hidden by default 

[x] the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again

[x] when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container 

[x] when a new feed is loaded by the loadFeed function the content changes


## Project Setup & Installation
### Get the git

 - Fork, clone or download the project here on github. Use git to clone
   the repository to your local system 
 - open terminal 
 - Navigate to the parent directory in which you intend to install
   the project
 - `$ git clone https://github.com/cajoue/frontend-nanodegree-feedreader.git`

This will create, and install files to, the project directory **frontend-nanodegree-feedreader** 

### Run on local Server
- open terminal
- Navigate to the root of the project directory 
- `$ python -m SimpleHTTPServer 8080 `
to run on port 8080 

- open browser (http://localhost:8080/)
- **index.html** should load automatically

## Running the Application
The Feed Reader App and the results of the Jasmine tests will load on the page.

Jasmine reports successful and failed tests at the bottom of the page.
- Green dots are successful tests
- Red crosses are failed tests

Successes are reported in Green text

Fails are reported in Red text

### The Tests
- RSS Feeds: are defined
- RSS Feeds: each have a URL
- RSS Feeds: each have a name
- The Menu: should be hidden by default
- The Menu: changes visibility when the menu icon is clicked
- Initial Entries: has at least one entry in the feed container
- New Feed Selection: changes the content in the feed container

### Callbacks
loadFeed() is asynchronous 

Callback functions make use of Jasmine's beforeEach and asynchronous done() function to ensure that the asynchronous feeds are loaded before they are tested.

##Technologies Used
- [Jasmine](http://jasmine.github.io/)
- JavaScript
- jQuery

## Helpful resources
### Jasmine
[Jasmine](http://jasmine.github.io/2.2/introduction.html)

### Forum
[New Feed Selection test](https://discussions.udacity.com/t/new-feed-selection-test/15741)
### jQuery
[.hasClass()](http://api.jquery.com/hasClass/)

[Triggering Event Handlers](https://learn.jquery.com/events/triggering-event-handlers/)

[.trigger()](http://api.jquery.com/trigger/)

[.first()](https://api.jquery.com/first/)

### Other
[Testing a simple toggle class show and hide with Jasmine](https://gist.github.com/davilious/9503539)

My reviewer :)
