

## Laravel 5 Memcache Driver

Use the below for older versions of laravel 5
```shell
composer require "wawa/laravel-memcache:*"
```

Add the memcache service provider in app/config/app.php:

```php
Wawa\Memcache\MemcacheServiceProvider::class,
```

You may now update your config/cache.php config file to use memcache
```php
	'default' => 'memcache',
```

You may now update your config/session.php config file to use memcache

```php
	'driver' => 'memcache',
```


