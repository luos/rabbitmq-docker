# Single Node Exercise
Prerequisites:

* Git
* Docker
* Docker-compose (part of docker in newer versions)

# Cloning the repository

```
git clone https://github.com/luos/rabbitmq-docker
```

Go to the directory "single-node". 

```
cd single-node
docker-compose up
```

# Obtaining a shell in the container

Open a new tab or terminal and start a shell in the container:

```
docker-compose exec rmq bash
```

Check the status of RabbitMQ

```
rabbitmqctl status
```

Enabling the management plugin

```
rabbitmq-plugins enable rabbitmq_management
```

# Open management interface

http://localhost:15672   




