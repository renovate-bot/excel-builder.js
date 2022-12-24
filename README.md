excel-builder-webpacker.js
================
An excel-builder version which support Webpack and RequireJS
This is a fork from excel-builder which wasn't maintained.

Documentation at http://excelbuilderjs.com/. This is slightly outdated, but includes a 'cookbook' and some
API documentation. New site coming soon with up-to-date documentation, and ability to contribute - see [https://github.com/stephenliberty/excel-builder-site](https://github.com/stephenliberty/excel-builder-site)

## License
[MIT License](LICENSE.md)

### Note (2022-05-01)

The original License was a dual MIT/GPLv3 license but that was a little confusing. However, we got some great news recently which was to receive Stephen Liberty's blessing (who is the original author of [excel-builder.js](https://github.com/stephenliberty/excel-builder.js)) to convert to a single MIT License which is more permissive, see the entire license discussion in the issue [#2](https://github.com/ghiscoding/excel-builder.js/issues/2#issuecomment-1114279973). I want to provide again my big thanks to Stephen's hard work in creating Excel-Builder which is still used by many of us, thank you so much.

Installing via NPM
------------------

	npm install excel-builder-webpacker


Building for web
----------------

Install Grunt:

	npm install -g grunt-cli

Install dependencies:

	npm install

Build & uglify:

	grunt

Distributables
---------------
excel-builder.compiled.js -> All files in the EB package and all dependencies.

excel-builder.dist.js -> All files in the EB package. Requires lodash and jszip scripts to be loaded on the page.

Contributing
-------------

Originally this project was sort of sponsored by a previous company I worked for. Unfortunately now it has no backing, and my time is very limited while I work on side projects to help make ends meet. If you use bountysource or contribute via paypal (to stephen@liberty-irm.com) to open up bounties on issues, it is very, very likely that I will add features and fix issues sooner than later.

Otherwise, if you have the ability to contribute yourself, please just do so as normal - I'll review and pull changes as they come in as quickly as I can.
