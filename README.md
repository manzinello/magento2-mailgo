# 💌 Mailgo for Magento 2

Mailgo module for Magento 2

<https://mailgo.dev/docs/magento/>

## Installation

### Composer / Packagist

```
composer require manzinello/mailgo
```

<https://packagist.org/packages/manzinello/mailgo>

### Manually

Clone the repository (<https://github.com/manzinello/magento2-mailgo>) anche copy the content in the folder `/app/code/Manzinello/Mailgo`

## Enable the extension

```
php bin/magento module:enable Manzinello_Mailgo
```

then

```
php bin/magento setup:upgrade
```

and maybe

```
php bin/magento setup:static-content:deploy
```
