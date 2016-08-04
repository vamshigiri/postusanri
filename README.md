# Steps to install
download and install mongodb.
set the mongodb path and start the db using 'mongod'.
from root directory install seed json 'mongoimport --db olympics-dev --collection sports --type json --file server/sports-seed.json --jsonArray --drop'.
install nodejs and npm install to resolve dependencies.
install gulp with npm install -g gulp to install Gulp globally.
start node server using 'node server/app.js'.
Navigate to localhost:8181