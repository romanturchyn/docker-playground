# Dockers
This is a repo for docker sandbox


How to operate:

First of all you need to clone this repo to local /home directory.

Then go to the docker-playground folder and run command: "sudo chmod a+x run_docker_containers.sh"

After this you need to upload your AWS-credentials to Ansibe andd Terraform container volumes.
Please, place AWS-credentials files to: 
  ~/docker-playground/dockerfile-ansible/credentials - for Ansible
  ~/docker-playground/dockerfile-terraform/credentials - for Terraform

When it`s done you may return to the ~/docker-playground and run script - "./run_docker_containers.sh" and choose which container you need to run just now.

The script builds and automatically run container after build is over and you may work.
