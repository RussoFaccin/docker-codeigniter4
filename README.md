# Docker CodeIgniter 4!

Docker container for CodeIgniter4 development.

## Installation
Start a fresh CodeIgniter4 project
```
composer create-project codeigniter4/appstarter project-root
```
Enter project directory
```
cd project-root
```

Clone the repository
```
git clone git@github.com:RussoFaccin/docker-codeigniter4.git .
```
Start Docker container
```
docker-compose up -d
```
Start container (php-fpm) command line
```
docker exec -it <containerID> bash
```
Give folder permissions
```
chmod 777 -R writable
```