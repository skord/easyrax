# Just working through this

A repo for some easy ansible setups. Build and deploy your app with not a lot of thinking.

### Getting Started

Install Ansible. pip install pyrax.

run: ```ansible-playbook setup.yml```

This will setup keys and such for you and get you ready to go. 

Right now there's just what I felt like finishing in a hot minute to get a few boxes behind a load balancer and have docker installed. Eventually, I hope to have lots of different examples including zero downtime deploys, and other goodies, like replicated postgres. 

If you want to start up the three docker hosts:

``` ansible-playbook medium_docker_setup.yml -i ansible_hosts ```
