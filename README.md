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

## Built With

* [node-sass](https://www.npmjs.com/package/node-sass) - Sass Compiler
* [BrowserSync](https://www.browsersync.io/) - Local Server and Browser Refresh
* [npm-run-all](https://www.npmjs.com/package/npm-run-all) - So you can run multiple packages at once

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details