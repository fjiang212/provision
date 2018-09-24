# Ansible Container Exmaple
* Set up DevOps Virtual machine

## Hello-world
* Build docker image

```
login as vagrant
cd hello-world

# Build service docker image
sudo ansible-container build

# Verify service docker image is built 
sudo docker images

# Run service docker container
sudo ansible-container run

# Verify service docker container is running 
sudo docker images
curl http://localhost:4000

# Stop service docker container
sudo ansible-container run
```
