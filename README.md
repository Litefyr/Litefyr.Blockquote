# Block quote content element for Litefyr

[Demo](https://elements.litefyr.io/blockquote)

## Installation

This package is available via [packagist]. Run `composer require litefyr/blockquote --no-update` in your
`Litefyr.Distribution` package. After that, run `composer update` in your root directory.

> In order to work correctly you'll need a working [Litefyr] instance running. Here you'll find the basis [Distribution]

### Adjust build stack

Make sure following entry is add to your `pipeline.yaml`:

```yaml
packages:
  - package: ../Packages/Litefyr/Litefyr.Blockquote
```

[litefyr]: https://litefyr.io
[distribution]: https://github.com/Litefyr/Distribution
[packagist]: https://packagist.org/packages/litefyr/blockquote
