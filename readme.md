# Alpine Docker

Docker images based on https://github.com/iron-io/dockers/ using Alpine Linux.
 
- alpinerubynode: An Alpine Linux image with Ruby and Node installed.
- alpinejekyll: An Alpine Linux image with Jekyll and Bundler installed. Depends on alpinerubynode.

# Updating Docker Image

- `docker build -t imagename .`
- `docker images`
- Copy ID of image
- `docker tag ID terrarum/imagename:latest`
- `docker push terrarum/imagename`