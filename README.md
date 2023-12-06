# GO AMQP emitter example

An example of the AMQP emitter showed in the official RabbitMQ tutorial for "Topics": https://rabbitmq.com/tutorials/tutorial-five-go.html

## Usage

```bash
go run main.go "account.created" "CREATED test message"
go run main.go "account.jens.test" "JENS test message"
```