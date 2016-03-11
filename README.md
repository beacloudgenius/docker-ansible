Step 1: Add the ip address of your box into the inventory/hosts file

    atom inventory/hosts

Step 2: Pull down this role from the galaxy

    ansible-galaxy install angstwad.docker_ubuntu

Step 3: Run the docker play

    ansible-playbook docker.yml
