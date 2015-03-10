## React Component Boilerplate [![Dependency Status](https://david-dm.org/yahoo/flux-examples.svg)](https://david-dm.org/TYRONEMICHAEL/react-component-boilerplate)

I modified the following [repo](https://github.com/TYRONEMICHAEL/react-component-boilerplate) to use Browserify instead. I prefer writing my moduleds `Node Style` and having Browserfiy compile and bundle my app.

React-Browserify-Boilerplate lets you create a React component quickly and test quickly as well as thoroughly using Karma. Have your tests run continuously with the added benefit of testing in your favorite and least favorite browsers while also having access to developer tools. Win Win. This was born out of the following [thread](https://github.com/facebook/jest/issues/116).

I tried to keep this as unopinionated as possible.

### Setup

* Clone the repo
* Run `npm install`

### Building Your Component

* Run `npm start`
* Open `public/index.html` and view your awesome creation

### Testing Your Component

* Run `npm test`
* To have your  tests run continuously, just run `./node_modules/karma/bin/karma start karma.conf.js --no-single-run` or you can always change the Karma configuration file

### Contribution

* Special thanks to [iamrandys](https://github.com/iamrandys)
