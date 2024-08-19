# Meet Adguard Home network-wide blocking ads & tracking

![Welcome](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnSExt84LkcgzenJevQHk1u1NSHgnQx1SRag&s)

# Docker bookstack with traefik

BookStack is a free and open-source wiki software aimed for a simple, self-hosted, and easy-to-use platform. Based on Laravel, a PHP framework, BookStack is released under the MIT License. It uses the ideas of books to organise pages and store information.
# Running the container

If you’re using Docker compose you can do with SSH with bellow or use filebrowser app.

for bookstack you need to make new database, please make new DB from phpmyadmin. if you don't have DB server & phpmyadmin check here 

For DB Server: [mariadb](https://github.com/ipathum/docker-compose_with_treafik/blob/106638d2012b358ff9a9359ca6dcec71e8c9eb2e/mariadb/README.md)

For phpmyadmin: [myphpadmin](https://github.com/ipathum/docker-compose_with_treafik/blob/106638d2012b358ff9a9359ca6dcec71e8c9eb2e/phpmyadmin/README.md)

> mkdir bookstack

> cd bookstack

> touch docker-compose.yml

> nano docker-compose.yml # copy the contents from docker-compose.yml, save and exit.

> docker-compose up -d

If you’re using Rancher, Portainer, Open Media Vault, Unraid, or anything else with a GUI, just copy and paste the environment variables above into the form on the web page.
