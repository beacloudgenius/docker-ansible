Step 1: Add the ip address of your box into the inventory/hosts file

    atom inventory/hosts

Step 1.5: avoid galaxy SNI validation issue https://github.com/ansible/galaxy/issues/795

    sudo -H pip install -U urllib3

Step 2: Pull down this role from the galaxy

    ansible-galaxy role install geerlingguy.docker

Step 3: Run the docker play

    ansible-playbook docker.yml
