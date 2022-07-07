# RabbitMQ Demo 
Technologies: Kotlin, Spring, RabbitMQ and Docker.

This demo is a simple example to use RabbitMQ with Kotlin and Spring.

Before run the tests, use Docker to initiate the RabbitMQ image. Just run the command below:

### Initial Command to run image of RabbitMQ on Docker
```docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management```

- The default username and password is "guest".
- Access Management of RabbitMQ on http://localhost:15672/
    


