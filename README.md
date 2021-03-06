# SimpleYelp

This is a Yelp search app using the [Yelp API](https://www.yelp.com/developers/documentation).

Time spent: `13.5`

## Features

### Required

- [x] Search results page
   - [x] Table rows should be dynamic height according to the content height
   - [x] Custom cells should have the proper Auto Layout constraints
   - [x] Search bar should be in the navigation bar (doesn't have to expand to show location like the real Yelp app does).
- [x] Filter page. Unfortunately, not all the filters are supported in the Yelp API.
   - [x] The filters you should actually have are: category, sort (best match, distance, highest rated), radius (meters), deals (on/off).
   - [x] The filters table should be organized into sections as in the mock.
   - [x] You can use the default UISwitch for on/off states.
   - [x] Clicking on the "Search" button should dismiss the filters page and trigger the search w/ the new filter settings.
   - [x] Display some of the available Yelp categories (choose any 3-4 that you want).

### Optional

- [x] Search results page
   - [x] Infinite scroll for restaurant results
   - [x] Implement map view of restaurant results
- [ ] Filter page
   - [x] Radius filter should expand as in the real Yelp app
   - [x] Categories should show a subset of the full list with a "See All" row to expand. Category list is here: http://www.yelp.com/developers/documentation/category_list (Links to an external site.)
   - [ ] Implement a custom switch
- [ ] Implement the restaurant detail page.

## Walkthrough

![Video Walkthrough](demo.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

Credits
---------
* [Yelp API](https://www.yelp.com/developers/documentation)
* [Carthage](https://github.com/Carthage/Carthage)
* [OAuthSwift](https://github.com/dongri/OAuthSwift)
* [Alamofire](https://github.com/Alamofire/Alamofire)
* [NounProject](https://thenounproject.com/)
   * [Arrow-Down Icon](https://thenounproject.com/term/arrow-down/11584/)
* [Checkbox Icons](https://github.com/mancunianetz/Checkbox)
* [Codepath ios_yelp_swift](https://github.com/codepath/ios_yelp_swift)
