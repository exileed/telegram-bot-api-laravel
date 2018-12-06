Telegram Bot API - PHP SDK - Laravel Integration
==========================

> [Telegram Bot API](https://core.telegram.org/bots) PHP SDK. Lets you develop Telegram Bots easily! Supports Laravel out of the box.

<p align="center">
<a href="https://travis-ci.org/exileed/telegram-bot-api-laravel"><img src="https://img.shields.io/travis/exileed/telegram-bot-api-laravel.svg?style=flat-square" alt="Build Status"/></a>
<a href="https://github.com/exileed/telegram-bot-api-laravel/releases"><img src="https://img.shields.io/github/release/exileed/telegram-bot-api-laravel.svg?style=flat-square" alt="Latest Version"/></a>
<a href="https://packagist.org/packages/exileed/telegram-bot-api-laravel"><img src="https://img.shields.io/packagist/dt/exileed/telegram-bot-api-laravel.svg?style=flat-square" alt="Total Downloads"/></a>
</p>

### Install

Require this package with composer using the following command:

```bash
composer require exileed/telegram-bot-api-laravel
```

After updating composer, add the service provider to the `providers` array in `config/app.php`

```php
Telegram\Bot\Laravel\TelegramServiceProvider::class,
```

Add facade to the `aliases` array in `config/app.php`
```php
'Telegram' => Telegram\Bot\Laravel\Facades\Telegram::class
```

**Laravel 5.5** uses Package Auto-Discovery, so doesn't require you to manually add the ServiceProvider and Facade.





## Documentation

@Todo


## License

This project is released under the [BSD 3-Clause][link-license] License.
