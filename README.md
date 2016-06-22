# Feed Reader App Testing

The Feed Reader App loads feeds from different sources using the Google Feed Reader API. The Jasmine testing framework was used to test that:

* the default initial loaded feed isn't empty
* the entries have non-empty name and URL
* the toggle menu is hidden by default
* clicking the menu icon toggles it's visibility
* the content is changed when a new feed is loaded

### Run it

1. Download or clone [this](https://github.com/leticialourenco/frontend-nanodegree-feedreader.git) repository
2. Open `index.html` in a browser
3. Test status will be visible at the bottom of the page

### Technologies

* JavaScript
* jQuery
* AJAX
* HTML & CSS
* Jasmine - Behavior-Driven JavaScript
* Google Feed Reader API