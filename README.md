## Enable MySQL Query logging
```
mkdir app/etc/dev && curl -o app/etc/dev/di.xml https://raw.githubusercontent.com/aabumuslimov/magento2_debug_di_ove
rwrite/master/app/etc/dev/di.xml && bin/magento cache:clean
```

## Disable MySQL Query logging
```
rm -rf app/etc/dev && bin/magento cache:clean
```
