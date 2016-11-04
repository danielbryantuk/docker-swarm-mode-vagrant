# docker-swarm-mode-vagrant

This project is to similify the setup for [Docker Swarm Mode][1] with Vagrant.

It will automatically create a swarm cluster of Docker, and the first node will be the manager and others will be worker.


# Usage

The three Vagrant instances (master and two workers) can be initialised using the following command:    

    vagrant up



# Play with it

Run the Swarm manager 

	vagrant ssh node-1


```
docker info
docker node ls
```

# References
[Swarm mode overview][1]

[1]: https://docs.docker.com/engine/swarm/
