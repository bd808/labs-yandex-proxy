Yandex reverse proxy
====================

Configure nginx running on a Wikimedia Labs instance to act as a reverse proxy
to the Yandex.XML search API.

Installation
------------

1. Create instance
2. Assign the instance a static IP address via horizon.wikimedia.org
3. sudo apt-get install nginx-light
4. sudo cp proxy.conf /etc/nginx/sites-enabled/default
5. sudo service nginx restart
