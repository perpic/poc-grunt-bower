# Install dependencies

## Install grunt

<img align="right" height="150" src="http://gruntjs.com/img/grunt-logo.png">

[Grunt](http://gruntjs.com/getting-started) is our task runner. We use it to build less files into CSS, concat and minify JS files, generate sprites, etc.

First, you'll need to install Grunt's command line interface (CLI):

`$ npm install -g grunt-cli`

## Install bower

<img align="right" height="150" src="http://bower.io/img/bower-logo.png">

[Bower](http://bower.io/) is our package manager. We use it to load **jquery**, **Twitter Bootstrap**, and other components we use in our site.

Install bower:

`$ npm install -g bower`

# Init project

## Install grunt and plugins

Grunt setup involves two files: **package.json** and **Gruntfile.js**

To install grunt and the plugins needed in this project run:

`$ npm install`

## Install bower components

Bower setup involves two files: **bower.json** and **.bowerrc**

To install all bower components needed in this project run:

`$ bower install`

# Build for production

`$ grunt build`
