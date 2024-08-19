# authentik  identity provider and secure login for services & web apps

![Welcome](https://repository-images.githubusercontent.com/230885748/19f01d00-8e26-11eb-9a14-cf0d28a1b68d)

# Docker authentik with Traefik

authentik is an open-source Identity Provider that emphasizes flexibility and versatility. It can be seamlessly integrated into existing environments to support new protocols. authentik is also a great solution for implementing sign-up, recovery, and other similar features in your application, saving you the hassle of dealing with them.

# Running the container

If you’re using Docker compose you can do with SSH with bellow or use filebrowser app.

> mkdir authentik

> cd authentik

> touch docker-compose.yml

> nano docker-compose.yml # copy the contents from docker-compose.yml and save, exit

> openssl rand -base64 36 # for generate a secret key for .env file.

> touch .env # copy the contents from .env and change values, and save, exit

> docker-compose up -d

If you’re using Rancher, Portainer, Open Media Vault, Unraid, or anything else with a GUI, just copy and paste the environment variables above into the form on the web page.
