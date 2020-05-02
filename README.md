# DRONE ANSIBLE PLAYBOOK

Source code for install Drone using Ansible tutorial.

## PREREQUISITES

You need replace those variables with your own:

+ `YOUR_SERVER_IP_ADDRESS`: Server ip address.
+ `YOUR_DOMAIN`: Drone domain address.
+ `YOUR_EMAIL`: Let's Encrypt registration email address.
+ `YOUR_DRONE_RPC_SECRET`: Authenticate the RPC connection to the Drone server.
+ `YOUR_DRONE_ADMIN_USER`: Drone admin user.
+ `YOUR_DRONE_GITHUB_CLIENT_ID`: GitHub client id.
+ `YOUR_DRONE_GITHUB_CLIENT_SECRET`: GitHub client secret.

## RUNNING PLAYBOOK

```bash
ansible-playbook drone.yml -i ./inventories/host.yaml
```
