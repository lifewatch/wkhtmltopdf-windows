wkhtmltopdf-windows
================

This Repo contains the Windows (MSVC 2015) Binaries for Windows Vista or later; bundles VC++ Runtime 2015.
[wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

All pre-compiled binaries can be found here: [https://github.com/wkhtmltopdf/packaging](https://github.com/wkhtmltopdf/packaging)

## PHP packages

For Laravel 5.x [github.com/wemersonjanuario/laravelpdf](https://github.com/wemersonjanuario/laravelpdf)
Non Framework [github.com/wemersonjanuario/pdf](https://github.com/wemersonjanuario/pdf)


## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.6'.

In case this package does _not_ work on your system, try installing the matching system packages from here: [http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html).

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for Windows with:

    php composer.phar require lifewatch/wkhtmltopdf-windows "0.12.6"


The binaries will then be located at:

    vendor/lifewatch/wkhtmltopdf-windows/bin/wkhtmltopdf-windows

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/32bit/wkhtmltopdf.exe.bat and vendor/bin/64bit/wkhtmltopdf.exe.bat
