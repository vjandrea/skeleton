# :package_name

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace
```:author_name```      // author name in Title Case
```:author_username```  // username lowercase
```:author_website```   // website lowercase
```:author_email```     // email address lowercase
```:package_name```     // package name lowercase
```:package_name_cap``` // package name CamelCase
```:package_description```  // package description untouched
```:vendor_name```      // vendor name lowercase
```:vendor_name_cap```  // vendor name CamelCase
with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Install

Via Composer

``` bash
$ composer require :vendor_name/:package_name
```

## Usage

``` php
$example = new :vendor_name_cap\:package_name_cap();
echo $example->echoPhrase('Hello, :vendor_name_cap!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email :author_email instead of using the issue tracker.

## Credits

- [:author_name][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/:vendor_name/:package_name.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/:vendor_name/:package_name/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/:vendor_name/:package_name.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/:vendor_name/:package_name.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/:vendor_name/:package_name.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/:vendor_name/:package_name
[link-travis]: https://travis-ci.org/thephpleague/:package_name
[link-scrutinizer]: https://scrutinizer-ci.com/g/:vendor_name/:package_name/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/:vendor_name/:package_name
[link-downloads]: https://packagist.org/packages/:vendor_name/:package_name
[link-author]: https://github.com/:author_username
[link-contributors]: ../../contributors
