myspots-nodejs
==============

the myspots nodejs app

# description

As we walk around the world, I would like to describe my favorite spot by highlighting something that I find is special. 

# features

Here is a list of features that this application will provide. More or less a list of APIs that the application can receive and send via GET, POST, and DELETE.

## creating a spot

To create a spot, you need the following:

1. Geo coordinates (long,lat)
2. Name of spot
3. Special feature description

## listing spots

To list spots, you need the following:

1. Current location
2. Radius limit

## list one spot

To list one spot, you need to POST:

1. ID of spot

## directions to next spot

When looking for directions from your current location to a spot, you need to POST:

1. Current location
2. ID of spot for destination

## removing a spot

1. Name of spot

# tdd

I have chosen [Mocah](http://visionmedia.github.io/mocha/#installation) for the testing framework (until something else looks better).

## running tests

To run the tests, type the following into your terminal at the root level of this project:

    mocah


# resources

Here is a list of resources that we might need to use for reference:

1. https://developers.google.com/maps/documentation/geocoding/#Geocoding
2. http://nodejs.org/
3. http://docs.mongodb.org/manual/applications/geospatial-indexes/
4. http://www.yelp.com/developers/documentation/v2/search_api
5. https://nodejsmodules.org/pkg/mocha
6. http://visionmedia.github.io/mocha/
7. https://help.github.com/articles/github-flavored-markdown

# tasks

- [ ] design schema
- [ ] add express files
- [ ] add tests for adding a spot
- [ ] add tests for listing spots
- [ ] add tests for removing spots