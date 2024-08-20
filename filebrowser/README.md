# Meet File Browser, a Small but Mighty Web File Browser

![Welcome](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR-Wb3J4YCgYm37vTmYLRWKTFbcRYW5bGYS1g&s)

# Docker filebrowser with traefik

filebrowser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory. It can be used as a standalone app.
# Running the container

If you’re using Docker compose you can do with SSH with bellow or use filebrowser app.

> mkdir filebrowser

> cd filebrowser

> touch docker-compose.yml

> nano docker-compose.yml `# copy the contents from docker-compose.yml, edit, save and exit.`

> touch filebrowser.db

> docker-compose up -d

If you’re using Rancher, Portainer, Open Media Vault, Unraid, or anything else with a GUI, just copy and paste the environment variables above into the form on the web page.
