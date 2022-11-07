# General Description
This is a containerlab topology file to start up a containerized instance of LibreNMS. For containerlab references check [here](https://containerlab.dev/). Using containerlab commands to start this topology the LibreNMS instance will be started on your docker host IP and port 8000.

It is based on the docker-compose LibreNMS repo accessible [here](https://github.com/librenms/docker).

# Environment
This was created based on:
- containerlab version 0.32.3
- MariaDB 10.5
- Redis 5.0
- LibreNMS 22.10.0
- msmtpd 1.8.22
