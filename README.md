
# Docker CodeIgniter 4!
Docker container for CodeIgniter4 development.

## Installation

- Create project folder
```
mkdir project-root
```

- Enter project directory
```
cd project-root
```

- Clone the repository
```
git clone git@github.com:RussoFaccin/docker-codeigniter4.git .
```

- Download the [latest CodeIgniter4 version](https://github.com/CodeIgniter4/framework/releases/latest), and extract it to your project root.
- Install dependencies
```
composer install
```

Run setup script
```
bin/setup
```
Access: http://localhost:8080/

## Commands
Start container
```
bin/start
```
Stop container
```
bin/stop
```