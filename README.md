# Development environment setup via Ansible

This repository contains an Ansible playbook to setup a development environment on a fresh Ubuntu 18.04 machine.

## To Run the Playbook

ansible-playbook base.yml

## Testing

'./build.sh' will build a fresh ubuntu container
'docker run --rm -it new-computer bash' will run the container and drop you into a shell. From there you can run the playbook.

## NOTE: MAC VERSION UNTESTED
