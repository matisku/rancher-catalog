## What is inside ownCloud Stack?
* [ownCloud Server](http://owncloud.org/) + Sidekick with uploads storage
* MariaDB Database + Sidekick with storage

## Info
* In default ownCloud stack will create "owncloud" MySQL database with osticket user.
* Once ownCloud will start, make sure you setup correct information in setup page.

## First Run
Once ownCloud Server starts: 
* Go to http://[IP]:[PORT] and login with default credentials: 
* During initial ownCloud setup, select "Storage & database" --> "Configure the database" --> "MySQL/MariaDB"
* Database user: root
* Database password: example
* Database name: pick any name
* Database host: replace "localhost" with "mysql"
