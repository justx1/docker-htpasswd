# docker-htpasswd

Generate an encrypted password file with Docker

## Usage

Clone the Dockerfile to your Docker host and build the Docker image:

```shell
docker build -t docker-htpasswd .
```

Run the container (replace username and password with desired values):

```shell
docker run --rm -ti docker-htpasswd username password > htpasswd
```
