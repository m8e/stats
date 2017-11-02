# Stats Generator for Facebook Groups

[![Latest Version](https://img.shields.io/github/release/php-earth/stats.svg?style=flat-square)](https://github.com/php-earth/stats/releases)
[![Build Status](https://img.shields.io/travis/php-earth/stats/master.svg?style=flat-square)](https://travis-ci.org/php-earth/stats)
[![MIT License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/php-earth/stats.svg?style=flat-square)](https://scrutinizer-ci.com/g/php-earth/stats/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/php-earth/stats.svg?style=flat-square)](https://scrutinizer-ci.com/g/php-earth/stats)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/c317a2f5-1fbe-4d76-a93c-8f0d98e61ef6/mini.png)](https://insight.sensiolabs.com/projects/c317a2f5-1fbe-4d76-a93c-8f0d98e61ef6)

PHP application for generating Facebook groups statistics.

<div align="center">
  <img src="https://cdn.rawgit.com/php-earth/logo/master/svg/indigo.svg" width="300">
</div>

## Documentation

The [Frequently Asked Questions](docs/faq.md) might have an answer to your question.

Read the following chapters for using this application locally:

* [Installation](docs/installation.md)
* [Configuration](docs/configuration.md)
* [Commands](docs/commands.md)


## Quick Usage

1. [Create](https://developers.facebook.com/) a new Facebook Application.

2. Install application with [Composer](https://getcomposer.org/)

    ```bash
    git clone git://github.com/php-earth/stats
    cd stats
    composer install
    ```

3. Configure Parameters

    The componser installation script creates `config/parameters.yaml` file
    for your settings. Configuration parameters are described in comments in the
    [parameters.yaml.dist](config/parameters.yaml.dist). Provide values for
    your application, date range and other configuration.

4. Generate Report

    ```bash
    bin/stats generate
    ```

    Insert the user access token generated manually via
    [Graph API explorer](https://developers.facebook.com/tools/explorer/).


## License and Contributing

This repository is released under the [MIT license](LICENSE).

You are welcome to [suggest improvements or open a ticket](/.github/CONTRIBUTING.md).
