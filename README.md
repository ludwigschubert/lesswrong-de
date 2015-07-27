# LessWrong Deutschland e.V.

[![Build Status](https://travis-ci.org/ludwigschubert/lesswrong-de.svg)](https://travis-ci.org/ludwigschubert/lesswrong-de)
[![Code Climate](https://codeclimate.com/github/ludwigschubert/lesswrong-de/badges/gpa.svg)](https://codeclimate.com/github/ludwigschubert/lesswrong-de)
[![Dependency Status](https://gemnasium.com/ludwigschubert/lesswrong-de.svg)](https://gemnasium.com/ludwigschubert/lesswrong-de)
[![Test Coverage](https://codeclimate.com/github/ludwigschubert/lesswrong-de/badges/coverage.svg)](https://codeclimate.com/github/ludwigschubert/lesswrong-de/coverage)

## About lesswrong-de

[lesswrong-de](http://github.com/ludwigschubert/lesswrong-de) is a website for Lesswrong Deutschland e.V.

It's built on [Proteus](https://github.com/thoughtbot/proteus), a collection of starter kits to help build static websites.

## Included Frameworks and Tools

* [HAML](http://haml.info):
  Simple template markup
* [Coffeescript](http://coffeescript.org):
  Write javascript with simpler syntax
* [Sass](http://sass-lang.com):
  CSS with superpowers
* [Bourbon](http://bourbon.io):
  Sass mixin library
* [Neat](http://neat.bourbon.io):
  Semantic grid for Sass and Bourbon
* [Bitters](http://bitters.bourbon.io):
  Scaffold styles, variables and structure for Bourbon projects.
* [Middleman Live Reload](https://github.com/middleman/middleman-livereload):
  Reloads the page when files change

## Getting Started

Set up your project in your code directory
```
git clone git@github.com:ludwigschubert/lesswrong-de.git lesswrong-de
cd lesswrong-de
```

Install dependencies:
```
bundle install
```

Run the server
```
middleman
```

Deploy to lesswrong.de
```
git push origin
```
…then watch the build process at [Travis.ci](https://travis-ci.org/ludwigschubert/lesswrong-de).


## Directories

Stylesheets, fonts, images, and JavaScript files go in the `/source/assets/` directory.
Vendor stylesheets and JavaScripts should go in each of their `/vendor/` directories.

## Contributing

If you have problems, please create a
[GitHub Issue](https://github.com/ludwigschubert/lesswrong-de/issues).

If there's sufficient demand, I can set up a staging site for pull requests. Let me know!

## Credits

[![thoughtbot](http://images.thoughtbot.com/bourbon/thoughtbot-logo.svg)](http://thoughtbot.com)

Proteus Middleman is maintained and funded by x[thoughtbot, inc](http://thoughtbot.com). Thank you to all of [the contributors](https://github.com/thoughtbot/proteus-middleman/contributors)!

## License

Copyright © 2015 [Lesswrong Deutschland e.V.](http://lesswrong.de).

Starter Kit Copyright © 2014–2015 [thoughtbot, inc](http://thoughtbot.com). Proteus Middleman is free software, and may be redistributed under the terms specified in the [license](LICENSE.md).
