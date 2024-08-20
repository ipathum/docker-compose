# phpMyAdmin administration tool for MySQL and MariaDB

![Welcome](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTedvcC7hIt1xxOqXzQI6dmxqKU_PkQiBZ_AQ&s)

# Docker phpmyadmin with traefik

phpMyAdmin is a free and open source administration tool for MySQL and MariaDB. As a portable web application written primarily in PHP, it has become one of the most popular MySQL administration tools, especially for web hosting services.
# Running the container

If you’re using Docker compose you can do with SSH with bellow or use filebrowser app.

for phpmyadmin you need MySQL or MariaDB.

For DB Server: [mariadb](https://github.com/ipathum/docker-compose_with_treafik/blob/106638d2012b358ff9a9359ca6dcec71e8c9eb2e/mariadb/README.md)

> mkdir phpmyadmin

> cd phpmyadmin

> touch docker-compose.yml

> nano docker-compose.yml # copy the contents from docker-compose.yml, save and exit.

> docker-compose up -d

If you’re using Rancher, Portainer, Open Media Vault, Unraid, or anything else with a GUI, just copy and paste the environment variables above into the form on the web page.
