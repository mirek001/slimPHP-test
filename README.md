# SlimPHP Hello World

This repository contains a very basic example of a [Slim Framework](https://www.slimframework.com/) application.

## Setup

1. Install dependencies using Composer:
   ```bash
   composer install
   ```
> Slim 4 requires a PSR-17/PSR-7 implementation such as `slim/psr7`.
2. Start the PHP built-in web server:
   ```bash
   php -S localhost:8080 -t public
   ```
3. Open `http://localhost:8080` in your browser and you should see `Hello, world!`.

## Files

- `composer.json` – project dependencies.
- `public/index.php` – Slim application entry point.
