# docker-compose
Docker compose files I have toyed with and used

Each folder contains a docker compose file that I altered to run cleanly on my system. Many of these I simply pasted into [Dockge](https://github.com/louislam/dockge). Some were more complex and were run using the docker CLI.

I like to have a directory in my home dir named "docker-data" which is where I put a seperate directory for each instance. Inside that the container creates the needed folders.

for simplicity, each compose file uses it's own DB (if needed). I have been debating whether this is the way to go or if I should just have a container for each of postgres, mariadb, mysql, etc. For now, it is explicit DB's in the compose file.

As time goes on, I will add a README to each folder with thoughts and tips specific to the respective application
