# zm-docker
dockerfile with ZoneMinder

Run "docker build -t zm-debian ." to build an image, or get image from DockerHub https://hub.docker.com/repository/docker/vplaton/zm-deb
Then run "docker run -dp 80:80 -v sql:/var/lib/mysql" to start Docker container.


PS: run on your host "sudo gpasswd -a username docker" were username is the name of your user which will run Docker to run it without using "sudo" command.
