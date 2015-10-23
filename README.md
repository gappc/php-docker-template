php-docker-template
===================

Simple template that uses docker to provide a php + mariadb environment.

## Checkout
```
$ git clone https://github.com/gappc/php-docker-template.git
```

## Start the environment
```
$ docker-compose up
```

## Usage
Put your code inside the "code" directory, access the project at http://localhost:8080. The database files can be found in the "datadir" directory.

Note: You have to adjust/delete the .gitignore file inside the "code" directory if you wish to enable version control for your code.
