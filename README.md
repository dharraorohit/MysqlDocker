Command to Build image from Dockerfile and creating container.
$ sudo docker build . -t pucsdsql
$ sudo docker run --name=pucsdsql -p 3306:3306 pucsdsql