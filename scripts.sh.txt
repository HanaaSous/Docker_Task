#!/bin/bash

docker build . --target server-image -t server-image
docker build . --target client-image -t client-image
docker run -p 8899:80 --name=server server-image
docker run --name=client client-image
