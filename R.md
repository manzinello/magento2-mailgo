# ◻️ Magento 2 - Whitelist CSP

A module to whitelist CSP in Magento 2

## Instructions

Substitute `https://www.example.com` in `/etc/config.xml`, then

```
php bin/magento module:enable Manzinello_CspWhitelist
```

and

```
php bin/magento setup:upgrade
```

and maybe

```
php bin/magento setup:static-content:deploy
```
