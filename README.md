# drupal-8-docker
Yoti Docker module for Drupal 8 including Yoti plugin.

## Set up
Clone this repos and run the following commands

`cd drupal-8-docker`

`docker-compose up -d` and add `--build` if you want to rebuild the image

Browse the link below and follow the instructions

`http://localhost:8008`

## Database Configuration
Enter the following details for the database

User Name `drupal`

Password `drupal`

Database Name `drupal`

Host `yoti-drupal-8-db`

## Yoti plugin setup
Please follow the instructions [here](https://github.com/getyoti/yoti-drupal-8) to set Yoti up.

## Removing docker containers
Run the following commands to remove docker containers:

`docker-compose stop` and

`docker-compose rm`
