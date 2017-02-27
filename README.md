# Trello Portfolio - Front End Components

This project is where the basic sketching for Trellofolio is happening. It's running off [Patternlab](http://patternlab.io) and uses a combination of JSON and Mustache templates. 

## Getting set up
1. Clone the repo. 
2. `npm install`
3. `gulp patternlab:serve` - will start at localhost on port 3000. 

If you have problems with Gulp you may need to update. [See this Github issue for details.](https://github.com/pattern-lab/edition-node-gulp/issues/51)

---

### List all of the available commands

To list all available commands type:

    gulp patternlab:help

### Watch for changes and re-generate Pattern Lab

To watch for changes, re-generate the front-end, and server it via a BrowserSync server,  type:

    gulp patternlab:serve

BrowserSync should open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Where does the magic happen? 
Global placeholder data can be inspected in `sources/_data/data.json`. In most cases, I have defined component-specific placeholder data, which can be found in `sources/_patterns/[components|layouts]/[pattern].json`. It's not particularly well formatted or structured at this point. Nor are the HTML templates, for that matter. 
