# hackernews-webscrape CLI

Is written Node.js to web-scrape the "https://news.ycombinator.com/" 
website to create a CLI app that returns top stories in a ranked .JSON format.


## How to install
 * cd into the project's directory and run:
 * npm run install-hackernews

Note: If you don't already have NPM installed, you can get it here: https://nodejs.org/en/download/

## How to run
Once you've installed the app, simply type any of the command flags available: 
 * hackernews --posts [number of posts]  
 * hackernews -p [number of posts]  retrieve number of posts into the terminal. 

 Note:
 * Default number of posts returned is 30 if you run just hackernews. 
 * This CLI app is global, i.e., you can run hackernews cmd in Desktop or any other directory.

## Libraries used:
- cheerio for HTML elements selection
- node-fetch for fetch API
- commander for running the program from a cmd line and allowing custom command flags
  such as: hackernews -p 40, and hackernews --help.
