## DestinyStatus

[![Join the chat at https://gitter.im/TrackerNetwork/DestinyStatus](https://badges.gitter.im/TrackerNetwork/DestinyStatus.svg)](https://gitter.im/TrackerNetwork/DestinyStatus?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/TrackerNetwork/DestinyStatus.svg?branch=master)](https://travis-ci.org/TrackerNetwork/DestinyStatus) [![Coverage Status](https://coveralls.io/repos/TrackerNetwork/DestinyStatus/badge.svg?branch=master&service=github)](https://coveralls.io/github/TrackerNetwork/DestinyStatus?branch=master)

### Community, please help us build this site! We are accepting all pull-requests that are in the spirit of the site.  For all other ideas and concepts, please create an issue, we can figure out something!

This project is based on the Laravel framework [v4.2].

Please [read these instructions](https://laravel.com/docs/4.2#server-requirements) on how to configure your server to get started.

### Project dependecies:

* PHP >= 5.4
* Mcrypt extension
* [Node.js](https://nodejs.org)
* [Composer](https://getcomposer.org)

### Install the framework

1. `composer install`
2. `php artisan key:generate`

### Compile CSS/JS

1. Install bower: `npm install -g bower`
2. Install grunt: `npm install -g grunt-cli`
3. Install dependencies:
    * `bower install`
    * `npm install`
4. Build:
    * Local: `grunt`
    * Production: `grunt --production`
