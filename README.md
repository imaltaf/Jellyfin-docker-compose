# Jellyfin-docker-compose

the ports section maps port 8096 on the container to port 8096 on the host machine. The PUBLIC_URL environment variable is set to the desired domain name. Note that you'll need to replace jellyfin.example.com with your actual domain name.

The volumes section creates named volumes for the Jellyfin configuration and cache data. You can start the Jellyfin container by running docker-compose up -d in the same directory as the docker-compose.yml file.
