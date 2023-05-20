mirzaarehman Menus
=================
[![Source](http://img.shields.io/badge/source-mirzaarehman/menus-blue.svg?style=flat-square)](https://github.com/mirzaarehman/menus)
[![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://tldrlegal.com/license/mit-license)

---

Easily create dynamic menus from within your Laravel 5 application. Originally developed for [FusionCMS](https://github.com/fusioncms/fusioncms), an open source content management system.

mirzaarehman Menus was based off of Lavary's [Laravel Menu](https://github.com/lavary/laravel-menu) package with support for the mirzaarehman Shinobi package.

The package follows the FIG standards PSR-1, PSR-2, and PSR-4 to ensure a high level of interoperability between shared PHP code. At the moment the package is not unit tested, but is planned to be covered later down the road.

Documentation
-------------
You will find user friendly and updated documentation in the wiki here: [mirzaarehman Menus Wiki](https://github.com/mirzaarehman/menus/wiki)

Quick Installation
------------------
Begin by installing the package through Composer.

```
composer require mirzaarehman/menus
```

Once this operation is complete, simply add the service provider class and facade alias to your project's `config/app.php` file:

#### Service Provider
```php
mirzaarehman\Menus\MenusServiceProvider::class,
```

#### Facade
```php
'Menu' => mirzaarehman\Menus\Facades\Menu::class,
```

And that's it! With your coffee in reach, start building out some awesome menus!
