## Application file permissions

As in all server environments, your application needs the correct file permissions to work properly. You can change the files throughout the container, so you won't care if the user exists or has the same ID on your host.

`docker-compose exec php chown -R www-data:www-data /var/www/html`