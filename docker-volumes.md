# Docker Volumes
# What are Docker Volumes?

* Docker volumes are file systems mounted on Docker containers to preserve data generated by the 
  running container.

* The volumes are stored on the host, independent of the container life cycle. This allows users to
  back up data and share file systems between containers easily.

# Getting Started With Docker Volumes

* There are different ways to mount a Docker volume while launching a container. Users can decide
  between the -v and the --mount flags, which are added to the docker run command.

# How to Create a Docker Volume
* To create a Docker Volume use the command:
	* docker volume create [volume_name]

