# nextcloud

docker-compose up -d

------------------------------

# owncloud

docker run -d -p 80:80 -p 443:443 -v /var/owncloud/config:/var/www/html/config -v /var/owncloud/data:/var/www/html/data owncloud
