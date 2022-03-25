# Sample WordPress template

This is a basic WordPress site that is hosted in a Docker container. The Docker-Compose file creates WordPress, MySQL, and phpMyAdmin instance.

This configuration creates a local wp-content folder for access to the code for developmental purposes. A local .env file must be created to set the MySQL database name, username, and password.

Once cloned and Docker is installed, all that is needed is to type into the terminal:
  docker-compose up -d 
and the services will be installed.
