# Pimcore Project Skeleton 

This skeleton should be used by experienced Pimcore developers for starting a new project from the ground up. 
If you are new to Pimcore, it's better to start with our demo package, listed below 😉

## Getting started
```bash
ddev start
ddev composer install
ddev exec ./vendor/bin/pimcore-install --admin-username=admin --admin-password=admin \
--mysql-username=db --mysql-password=db --mysql-database=db \
--mysql-host-socket=ddev-pimcore-db --mysql-port=3306 \
--no-interaction
# Add elasticsearch
ddev get ddev/ddev-elasticsearch
```
    
5. :heavy_check_mark: DONE - You can now visit your pimcore instance:
    * The frontend: <https://pimcore.ddev.site>
    * The admin interface, using the credentials you have chosen above:
      <https://pimcore.ddev.site/admin>

## Other demo/skeleton packages
- [Pimcore Basic Demo](https://github.com/pimcore/demo)
