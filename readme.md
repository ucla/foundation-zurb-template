# UCLA's ZURB Foundation for Sites Template

This is based off of the official ZURB Template for use with the UCLA fork of [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript module bundling with webpack
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Installation

### Build Tools / Dependencies

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

To set up the template, first download it with Git (replacing `projectname` with the name of the desired install location to be created, if any):

```bash
git clone https://github.com/ucla/foundation-zurb-template projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
bower install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

### Framework

Since we're using a forked version of Zurb Foundation itself we'll just pull it in directly (for now!) as a Git Submodule and stick it in the bower_components directory to keep any pathing issues out of the way (yeah yeah, I kow).

You can Run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

## Updating

After making sure you've pulled down the latest version from github, run `npm install` and `bower install`


## Usage

Finally to run Gulp:

```bash
npm start
```

Your finished site will be created in a folder called `dist`, viewable at this URL: `http://localhost:8000`

To create compressed, production-ready assets:

```bash
npm run build

