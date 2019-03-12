### Boilerplate for HTML Projects

This is my workflow for HTML projects using SASS as a preprocessor and 7-1 architecture.  You can reference [7-1 here](https://sass-guidelin.es/#the-7-1-pattern).

I hope this helps anyone looking to do very basic setup and automation of their HTML/SASS dev process.  Yes, there are better ways, but this is mine for now.  I'll update this as my process evolves.

### Prerequisites

You will need Browsersync installed as either a dependency or globally.  It is not included in the package.json as I have it installed globally.

```
npm install -g browser-sync
```

or
```
npm install browser-sync --save-dev
```

## Optional But Handy

There are 2 files included that are not necessary, but helpful if you suck with colors.  (Damn it Jim, I'm a developer not a designer!)

* colors.html
* sass/pages/colorPageLayout.scss

This is based completely off the work of Natalya Shelburne (eg. all those fancy variables are hers.)  You can read more about here ideas on color theory here:

* [Practical Color Theory for People Who Code](https://tallys.github.io/color-theory/) - Color Selector

I use this file by changing the $first-color variable to the HSLA of my primary site color, then pick and choose from the color palette it generates for other things.

If you don't want to use this and don't want it in your final code, you'll need to remove those 2 files PLUS go into sass/abstracts/variables and remove all of her code.  It's clearly marked at the bottom of the variables file.

## Built With

* [node-sass](https://www.npmjs.com/package/node-sass) - Sass Compiler
* [BrowserSync](https://www.browsersync.io/) - Local Server and Browser Refresh
* [npm-run-all](https://www.npmjs.com/package/npm-run-all) - So you can run multiple scripts at once

My code editor is Sublime 3 and I use the following packages:

* [All Autocomplete](https://github.com/alienhard/SublimeAllAutocomplete) - Extends the default autocomplete to find matches in all open files. 

* [AutoFileName](https://packagecontrol.io/packages/AutoFileName) - A GODSEND when you're adding a lot of image files.

* [HTML-CSS-JS-Prettify](https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify) - HTML, CSS, JavaScript, JSON, React/JSX and Vue code formatter for Sublime Text 2 and 3 via node.js

* [SassBeautify](https://packagecontrol.io/packages/SassBeautify) - A Sublime Text plugin that beautifies Sass files.

* [CSS3](https://packagecontrol.io/packages/CSS3) - The most complete CSS support for Sublime Text 3

* [Emmet](https://packagecontrol.io/packages/Emmet) - Emmet for Sublime Text

* [Emmet Cheatsheet](https://docs.emmet.io/cheat-sheet/) - Here's a handy Emmet cheatsheet if you need it


## Final Thoughts

I'll update this when I start producing more final build projects.  Right now, this gets me up and running to test and play with things and not worry about constantly refreshing the browser.  Other scripts will come as I need them and find I use them frequently.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

