# Meet Adguard Home network-wide blocking ads & tracking

![Welcome](https://www.myhome.zone/wp-content/uploads/2021/05/Beitragsbild_AdguardHome.png)

AdGuard Home is a network-wide software for blocking ads & tracking. After you set it up,
it’ll cover ALL your home devices, and you don’t need any client-side software for that. 
With the rise of Internet-Of-Things and connected devices, 
it becomes more and more important to be able to control your whole network.

# Running the container

If you’re using Docker compose you can do with SSH with bellow or use filebrowser app.

> mkdir adguardhome

> cd adguardhome

> touch docker-compose.yml

> nano docker-compose.yml # copy the contents from docker-compose.yml

> docker-compose up -d

If you’re using Rancher, Portainer, Open Media Vault, Unraid, or anything else with a GUI, just copy and paste the environment variables above into the form on the web page.
