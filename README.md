# RabbitMQ-Exemple

### Exemple How to use RabbitMQ + .Net Core 3.1

Based on the exemple of RabbitMQ's own documentation: 
(https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)

### How to install RabbitMQ Server on Linux (Ubuntu):
#### 1 - Install Erlang:

*sudo apt install erlang*

#### 2 - Install RabbitMQ Server:

*sudo apt-get install rabbitmq-server*

#### 3 - Enable the service of the RabbitMQ:

*sudo systemctl enable rabbitmq-server*

#### 4 - Start the RabbitMQ:

*sudo systemctl start rabbitmq-server*

#### 5 - Check status (optional):

*sudo systemctl status rabbitmq-server*

#### 6 - Install RabbitMQ Management

*sudo rabbitmq-plugins enable rabbitmq_management*

#### 7 - URL default:

*http://localhost:15672/*

