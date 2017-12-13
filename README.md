# docker-compose
Dockerized PHP dev environment w/ xdebug

I set this docker environment up to support PHP XDEBUG in JetBrains PHPStorm. The purpose is to have a bare-bones PHP environment to start developing in.

It runs an PHP web server at port 8080 inside the container but port 80 through the docker-compose configuration.

Zend Expressive Middleware framework skeleton app is installed. Code is in the www directory.

## Webstorm setup

The trick is to set up the debug proxy I guess.

Languages & Frameworks -> PHP -> Debug -> DBGp proxy:

- IDE Key=PHPSTORM
- HOST=[local ip]
- PORT=9000

Then a debug run configuration can be created like you'd hope.
