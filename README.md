# Freshworks CLI - Docker image

Freshworks docker image for creation of Freshworks Apps

## Image info
Built on alpine node 6.14 image as per freshworks requirements

https://developers.freshdesk.com/v2/docs/quick-start/

## Running this image

`docker run --rm --volumes $PWD:/app stapelpanda_freshworks_cli <COMMAND>`

Creation of app: `docker run --rm --volumes $PWD:/app stapelpanda_freshworks_cli create --template <template>`

Running app for development: `docker run --rm -p 10001:10001 --volumes $PWD:/app stapelpanda_freshworks_cli run`