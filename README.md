## Magento 2 Dutch Language Pack

```bash
composer require aveadev/magento-2-dutch-language-pack
php bin/magento setup:static-content:deploy nl_NL
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

