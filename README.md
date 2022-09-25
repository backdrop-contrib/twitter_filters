# Twitter Filters

Detects plain text hashtags, usernames and Twitter URLs in your content and
converts them to Twitter links or embeds.

Note: This module has pulled out the filter-specific bits of the full Twitter
module for sites that only need the filter-specific functionality without
requiring the more complex dependency stack with OAuth and Twitter API
integration. It won't make sense to have both this module and the full Twitter
module installed on the same site.

## Installation

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Instructions

- Once installed, text formats will have a number of new filters as options,
  allowing automatic conversion from simple text hashtags and usernames to
  Twitter links, and from Twitter status URLs to embedded Tweets.

Please view and contribute to the [Wiki](https://github.com/backdrop-contrib/twitter_filters/wiki) for further instructions.

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/twitter_filters/issues)

## Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn/), [CEDC.org](https://CEDC.org)

## Credits

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn/), [CEDC.org](https://CEDC.org)
- The larger [Twitter module](https://github.com/backdrop-contrib/twitter) that
  this code is taken from has a Backdrop version (maintained by [Graham Oliver](https://github.com/Graham-72)).
- The original Drupal version is maintained by Juan Pablo Novillo Requena
  (juampy), Chris Burgess (xurizaemon), michaek, James Walker (walkah), Jeff
  Eaton (eaton).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
