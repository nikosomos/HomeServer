# HomeServer

To start all the services run the following command
`docker compose up -d`


Example .env file
# Your timezone, https://en.wikipedia.org/wiki/List_of_tz_database_time_zones
TZ=America/Edmonton
# UNIX PUID and PGID, find with: id $USER
PUID=1000
PGID=1000
# The directory where data and configuration will be stored.
ROOT=D:\root
PLEX_CLAIM="<claim>"
PIHOLE_WEB_PW="<pw>"


How to get HACS
    Open a terminal
    Change directory to your Home Assistant configuration directory
    Run the HACS download script
        `wget -O - https://get.hacs.xyz | bash -`