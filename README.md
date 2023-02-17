# CodeIgniter 4 - PPDB (Penerimaan Peserta Didik Baru)

## Apa Itu CodeIgniter 4 - PPDB?

Codeigniter 4 - PPDB adalah aplikasi yang bisa digunakan oleh sekolah untuk melakukan penerimaan siswa baru, dengan fokus memberikan aplikasi dengan pelayanan yang lebih cepat dan dinamis sehingga dapat menyesuaikan lingkungan dari pengguna aplikasi.

## Installation & updates

`composer create-project codeigniter4/appstarter` then `composer update` whenever
there is a new release of the framework.

When updating, check the release notes to see if there are any changes you might need to apply
to your `app` folder. The affected files can be copied or merged from
`vendor/codeigniter4/framework/app`.

## Setup

Copy `env` to `.env` and tailor for your app, specifically the baseURL
and any database settings.

## Server Requirements

PHP version 7.4 or higher is required, with the following extensions installed:

- [intl](http://php.net/manual/en/intl.requirements.php)
- [mbstring](http://php.net/manual/en/mbstring.installation.php)

Additionally, make sure that the following extensions are enabled in your PHP:

- json (enabled by default - don't turn it off)
- [mysqlnd](http://php.net/manual/en/mysqlnd.install.php) if you plan to use MySQL
- [libcurl](http://php.net/manual/en/curl.requirements.php) if you plan to use the HTTP\CURLRequest library
