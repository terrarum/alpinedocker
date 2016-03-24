# Alpine Jekyll

A minimal Docker container for building Jekyll sites on Alpine Linux.

Possibly goes too far with the port and cmd commands.

# Updating Docker Image

docker build -t alpinerubynode .
docker images
    Copy ID of alpinerubynode image
docker tag ID terrarum/alpinerubynode:latest
docker push terrarum/alpinerubynode