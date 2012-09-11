FPDF for use with Symfony2
==============================

Uses FPDF 1.7

Setup
-----

those to `vendor/composer/autoload_namespaces.php`:

```php

// autoload_namespaces.php generated by Composer

$vendorDir = dirname(__DIR__);
$baseDir = dirname($vendorDir);

return array(
    ...
    'Fpdmerge_' => $vendorDir . '/fpdmerge/lib',
    ...
    )
```

Now run `php bin/vendors update` or `php bin/vendors install`.

Usage
-----

```php
$pdf = new \Fpdfmerge_Fpdfmerge;
```
