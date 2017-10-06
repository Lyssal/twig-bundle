# Installation

1. Update your `composer.json` :

```json
"require": {
    "lyssal/twig-bundle": "~x.y"
}
```

2. Update with Composer :

```sh
composer update
```

3. Add in your `AppKernel.php` :

```php
new Lyssal\TwigBundle\LyssalTwigBundle(),
```
