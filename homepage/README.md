# homepage  highly customizable application dashboard

![Welcome](https://gethomepage.dev/v0.8.13/assets/banner_light%402x.png#only-dark)

# Docker authentik with Traefik

homepage is a modern, fully static, fast, secure fully proxied, highly customizable application dashboard with integrations for over 100 services and translations into multiple languages. Easily configured via YAML files or through docker label discovery.
# Running the container

If you’re using Docker compose you can do with SSH with bellow or use filebrowser app.

> mkdir homepage

> cd homepage

> touch docker-compose.yml

> nano docker-compose.yml # copy the contents from docker-compose.yml. edit, save and exit

> touch .env # copy the contents from .env and change values, and save, exit

> mkdir icons

> mkdir images 

> docker-compose up -d

If you’re using Rancher, Portainer, Open Media Vault, Unraid, or anything else with a GUI, just copy and paste the environment variables above into the form on the web page.
