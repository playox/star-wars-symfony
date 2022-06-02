# Star Wars Symfony
This is a Symfony 6 template for the Star Wars exercise task. You can use this application to build a website using
Symfony 6, PHP8, Node and Docker. Fork this project or check it out with git to start the installation.

You only need [Docker Compose](https://docs.docker.com/compose/install/) to run this application locally. 
Checkout [Symfony Documentation](https://symfony.com/doc/current/index.html) for introduction.


## Installation
| Step                        | Command                                    |
|-----------------------------|--------------------------------------------|
| 1. Build docker containers  | `docker-compose up -d --build`             |
| 2. Install php dependencies | `docker-compose exec php composer install` |
| 3. Install npm dependencies | `docker-compose exec php npm install`      |
| 4. Build assets             | `docker-compose exec php npm run build`      |

You can access your local application via `http://localhost:8080`.

## Commands
| Step             | Command                        |
|------------------|--------------------------------|
| Start containers | `docker-compose start`         |
| Stop containers  | `docker-compose stop`          |
| Access container | `docker-compose exec php bash` |

