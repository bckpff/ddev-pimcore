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
```

- Point your virtual host to `my-project/public` 
- Open https://your-host/admin in your browser
- Done! 😎

4. Install pimcore and initialize the DB
    `docker-compose exec php vendor/bin/pimcore-install --mysql-host-socket=db --mysql-username=pimcore --mysql-password=pimcore --mysql-database=pimcore`
    * When asked for admin user and password: Choose freely
    * This can take a while, up to 20 minutes
    
5. :heavy_check_mark: DONE - You can now visit your pimcore instance:
    * The frontend: <http://localhost>
    * The admin interface, using the credentials you have chosen above:
      <http://localhost/admin>

## Other demo/skeleton packages
- [Pimcore Basic Demo](https://github.com/pimcore/demo)
