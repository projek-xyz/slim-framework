# Welcome to the slim-framework wiki!

[![LICENSE](https://img.shields.io/packagist/l/projek-xyz/slim.svg?style=flat-square)](LICENSE.md)
[![VERSION](https://img.shields.io/packagist/v/projek-xyz/slim.svg?style=flat-square)](https://github.com/projek-xyz/slim-skeleton/releases)
[![Build Status](https://img.shields.io/travis/projek-xyz/slim-framework/master.svg?style=flat-square)](https://travis-ci.org/projek-xyz/slim-framework)
[![Coveralls](https://img.shields.io/coveralls/projek-xyz/slim-framework/master.svg?style=flat-square)](https://coveralls.io/github/projek-xyz/slim-framework)
[![Code Climate](https://img.shields.io/codeclimate/coverage/github/projek-xyz/slim-framework.svg?style=flat-square)](https://codeclimate.com/github/projek-xyz/slim-framework/coverage)
[![Code Climate](https://img.shields.io/codeclimate/github/projek-xyz/slim-framework.svg?style=flat-square)](https://codeclimate.com/github/projek-xyz/slim-framework)
[![SensioLabs Insight](https://img.shields.io/sensiolabs/i/54d5b9b0-46bb-45b3-bf83-03cb483b4a81.svg?style=flat-square)](https://insight.sensiolabs.com/projects/54d5b9b0-46bb-45b3-bf83-03cb483b4a81)

## Requirements

- PHP 5.5.x or newer, since Slim 3 depends on it.
- HTTP Server, e.g. NginX or Apache either.
- MySQL Server 5.x or newer for main database.

## Installation

I've make this package available to install via `composer create-project` so make sure you've already have [composer](https://getcomposer.org/download/) installed globally in your system.

```bash
$ composer create-project dev projek-xyz/slim-skeleton my-app --prefer-dist
```

then enter `my-app` directory you just create and start the server.

```bash
$ cd my-app
$ php -S localhost:8888 -t public
```

Now, you should open [http://localhost:8888](http://localhost:8888) in your favorite web browser.
