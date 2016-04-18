Yandex reverse proxy
====================

Configure nginx running on a Wikimedia Labs instance to act as a reverse proxy
to the Yandex.XML search API.

Installation
------------

# Create instance
# Assign the instance a static IP address via horizon.wikimedia.org
# sudo apt-get install nginx-light
# sudo cp proxy.conf /etc/nginx/sites-enabled/default
# sudo service nginx restart
