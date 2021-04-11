# Docker_Task

- Create Apache server/client using Docker.

 

Please note the following:


1) Server side.

Download httpd from centos7.

Create a custom repo which contains httpd you just downloaded.

Run the server on port 8899.

Create a script to build the docker image and run the container.


2) Client side.

Add a request to get the custom repo from the server side.

Use this repo to install httpd.

Create a script to build the docker image.


3) Validation

Create a script to validate the download httpd rpm on client.

============================================================================================

==> please follow commands file
steps:
1) install docker and start it
2) create a new directory with 3 files
  a)Dockerfile. 
  b)scripts.sh which contains instructions to build server-image, client-image then runs conatainers from those images.
  c)validation.sh which contains a script to check if httpd is installed at client container.

