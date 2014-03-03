# InstantRetryProcessor

[![Build Status](https://travis-ci.org/swarrot/instant-retry-processor.png)](https://travis-ci.org/swarrot/instant-retry-processor)
[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/swarrot/instant-retry-processor/badges/quality-score.png?s=91ff54b237a9edc7c23d4c9d5a0413c2f39da876)](https://scrutinizer-ci.com/g/swarrot/instant-retry-processor/)

InstantRetryProcessor is a [swarrot](https://github.com/swarrot/swarrot) processor.
Its goal is to recall the processor when an error occured.

## Installation

The recommended way to install InstantRetryProcessor is through
[Composer](http://getcomposer.org/). Require the
`swarrot/instant-retry-processor` package into your `composer.json` file:

```json
{
    "require": {
        "swarrot/instant-retry-processor": "@stable"
    }
}
```

**Protip:** you should browse the
[`swarrot/instant-retry-processor`](https://packagist.org/packages/swarrot/instant-retry-processor)
page to choose a stable version to use, avoid the `@stable` meta constraint.

## Usage

See [swarrot documentation](https://github.com/swarrot/swarrot).

## Configuration

|Key                   |Default|Description                                            |
|:--------------------:|:-----:|-------------------------------------------------------|
|instant_retry_delay   |2000000|The delay in micro seconds to wait before trying again.|
|instant_retry_attempts|3      |The number of attempts before raising an exception.    |

## License

InstantRetryProcessor is released under the MIT License. See the bundled LICENSE file for details.
