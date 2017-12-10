# php-dev-env
Dockerized PHP dev environment w/ xdebug

I set this docker environment up to support PHP XDEBUG in JetBrains PHPStorm. The purpose is to have a bare-bones PHP environment to start developing in.

It runs an Apache2 web server at port 80 inside the container but port 8001 through the docker-compose configuration.

## Webstorm setup
Languages & Frameworks -> PHP -> Debug -> DBGp proxy:

IDE Key=PHPSTORM
HOST=<local ip>
PORT=9000
