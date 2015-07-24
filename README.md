# WP Thumbor

This is forked from [CodeKitchenBV/Thumbor](https://github.com/CodeKitchenBV/Thumbor) to include some modifications specific to our Statesman implementation.

Mainly:
* it pulls the settings from the Wordpress options table

## Installation

In composer.json:
```php
  "repositories": [
    ...
    {
      "type": "vcs",
      "url": "https://github.com/statesman/Thumbor"
    }
  ],
  "require": {
    ...
    "codekitcheneu/thumbor": "dev-master",
  },
```

Then activate the plugin and get the Thumbor info into the options table.
