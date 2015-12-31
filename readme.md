# ZURB Template

**Please open all issues with this template on the main [Foundation for Sites](https://github.com/ucla/foundation-sites/issues) repo.**

This is based off of the official ZURB Template for use with the UCLA fork of [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.10 or greater)
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

To create compressed, production-ready assets:

 `npm run build`
