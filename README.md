# Rialto

[![PHP Version](https://img.shields.io/packagist/php-v/danieldigitalart/rialto.svg?style=flat-square)](http://php.net/)
[![Composer Version](https://img.shields.io/packagist/v/danieldigitalart/rialto.svg?style=flat-square&label=Composer)](https://packagist.org/packages/danieldigitalart/rialto)
[![Node Version](https://img.shields.io/node/v/@danieldigitalart/rialto.svg?style=flat-square&label=Node)](https://nodejs.org/)
[![NPM Version](https://img.shields.io/npm/v/@danieldigitalart/rialto.svg?style=flat-square&label=NPM)](https://www.npmjs.com/package/@danieldigitalart/rialto)
[![Build Status](https://img.shields.io/travis/danieldigitalart/rialto.svg?style=flat-square&label=Build%20Status)](https://travis-ci.org/danieldigitalart/rialto)

A package to manage Node resources from PHP. It can be used to create bridges to interact with Node libraries in PHP, like [PuPHPeteer](https://github.com/danieldigitalart/puphpeteer/).

It works by creating a Node process and communicates with it through sockets.

## Requirements and installation

Rialto requires PHP >= 7.2 and Node >= 8.

Install it in your project:

```shell
composer require danieldigitalart/rialto
npm install https://github.com/danieldigitalart/rialto
```

## Usage

See our tutorial to [create your first bridge with Rialto](docs/tutorial.md).

An [API documentation](docs/api.md) is also available.

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
