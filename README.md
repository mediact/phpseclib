# phpseclib - PHP Secure Communications Library

[![Build Status](https://travis-ci.com/phpseclib/phpseclib.svg?branch=master)](https://travis-ci.com/phpseclib/phpseclib)

## Supporting phpseclib

- [Become a backer or sponsor on Patreon](https://www.patreon.com/phpseclib)
- [One-time donation via PayPal or crypto-currencies](http://sourceforge.net/donate/index.php?group_id=198487)
- [Subscribe to Tidelift](https://tidelift.com/subscription/pkg/packagist-phpseclib-phpseclib?utm_source=packagist-phpseclib-phpseclib&utm_medium=referral&utm_campaign=readme)

## Introduction

MIT-licensed pure-PHP implementations of an arbitrary-precision integer
arithmetic library, fully PKCS#1 (v2.1) compliant RSA, DES, 3DES, RC4, Rijndael,
AES, Blowfish, Twofish, SSH-1, SSH-2, SFTP, and X.509

* [Browse Git](https://github.com/phpseclib/phpseclib)

## Documentation

* [Documentation / Manual](http://phpseclib.sourceforge.net/)
* [API Documentation](https://api.phpseclib.org/master/) (generated by Doctum)

## Branches

### master

* Development Branch
* Unstable API
* Do not use in production

### 2.0

* Long term support (LTS) release
* Modernized version of 1.0
* Minimum PHP version: 5.3.3
* PSR-4 autoloading with namespace rooted at `\phpseclib`
* Install via Composer: `composer require phpseclib/phpseclib:~2.0`

### 1.0

* Long term support (LTS) release
* PHP4 compatible
* Composer compatible (PSR-0 autoloading)
* Install using Composer: `composer require phpseclib/phpseclib:~1.0`
* Install using PEAR: See [phpseclib PEAR Channel Documentation](http://phpseclib.sourceforge.net/pear.htm)
* [Download 1.0.19 as ZIP](http://sourceforge.net/projects/phpseclib/files/phpseclib1.0.19.zip/download)

## Security contact information

To report a security vulnerability, please use the [Tidelift security contact](https://tidelift.com/security). Tidelift will coordinate the fix and disclosure.

## Support

Need Support?

* [Checkout Questions and Answers on Stack Overflow](http://stackoverflow.com/questions/tagged/phpseclib)
* [Create a Support Ticket on GitHub](https://github.com/phpseclib/phpseclib/issues/new)
* [Browse the Support Forum](http://www.frostjedi.com/phpbb/viewforum.php?f=46) (no longer in use)

## Contributing

1. Fork the Project

2. Ensure you have Composer installed (see [Composer Download Instructions](https://getcomposer.org/download/))

3. Install Development Dependencies

    ``` sh
    composer install
    ```

4. Create a Feature Branch

5. (Recommended) Run the Test Suite

    ``` sh
    vendor/bin/phpunit
    ```
6. (Recommended) Check whether your code conforms to our Coding Standards by running

    ``` sh
    vendor/bin/phing -f build/build.xml sniff
    ```

7. Send us a Pull Request
