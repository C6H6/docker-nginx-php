# NGINX + PHP-FPM 7.2

Docker-compose config for NGINX web server and PHP 7.2 FPM.

# Instruction

  - Install [Docker](https://docs.docker.com/install/) and [Docker Compose](https://docs.docker.com/compose/install/)
  - Pull this repository
  - Go to root directory (with `docker-compose.yml` file) and run: `docker-compose up`
  - Server is running: `localhost:8000`

You can also:
  - Put your php files in `sources` directory (`index.php` is index file)
  - Edit server configuration: `configs/nginx.conf`

License
----

MIT
