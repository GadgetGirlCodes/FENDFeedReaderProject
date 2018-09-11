# Udacity Feed Reader Project

## Table of Contents

* [Project Overview](#projectoverview)
* [To Run the Project](#toruntheproject)
* [Included Tests](#includedtests)
* [Attribution](#attribution)
* [Contributing](#contributing)


## Project Overview

To implement learned skills in writing and executing a Jasmine test suite.

## To Run the Project

1. Download or clone the repository files.
2. If Jasmine isn't installed on your device, see [here](https://jasmine.github.io/setup/nodejs.html) for how to install it. I used the NodeJS version, and you can find [NodeJS here](https://nodejs.org/)

3. Once you have installed NodeJS and Jasmine, run index.html from the project root folder to view the page and its tests.

## Included Tests

1. "RSS Feeds"
   -"are defined": determines if the `allFeeds` variable has been defined and is not empty. This houses the different feeds on the feed reader.
   -"URL defined": determines if each feed in the `allFeeds` object has a "URL" value and that value is defined. This houses the links to each feed.
   -"name defined": determines if each feed in the allFeeds object has a "name" value and that value is defined. This houses the title of each feed link.
2. "The Menu"
   -"menu hidden default": determines if the navigation menu is hidden upon load of the page.
   -"menu visibility changes": determines if the navigation menu is shown and hidden when the menu icon is clicked.
3. "Initial Entries"
   -"loads initial entries": this is an asynchronous test that determines if the `loadFeed();` function loads a new `.entry` into the `.feed` section of the page upon initial load of the page.
4. "New Feed Selection"
   -"changes content": this is an asynchronous test that determines if the `loadFeed();` function loads different information for each `.entry` after the initial load of the page.

## Attribution

Thank you to Kehinde (FEND) in our Udacity Slack group for help with figuring out my last test "New Feed Selection". Also, thank you to Asmaa from Slack for a comment on Mitali {FEND}'s thread in the fend_live_help channel that lead me to finally figuring out what I did wrong.

Also, last but not least, thank you to Matthew Cranford for his walk-through on project 4. It can be found [here](https://matthewcranford.com/feed-reader-walkthrough-part-1-starter-code/).


## Contributing

This repository was created solely for the purpose of completing Udacity's Front End Nanodegree Program. Pull requests are welcome, but may not be accepted.