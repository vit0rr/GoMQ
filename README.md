# GoMQ
Hello-World RabbitMQ with GoLang

To run you'll need a RabbitMQ server running.
```bash
➜ docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.13-management
```


Run sender and receiver
```bash
➜ go run sender.go
➜ go run receive/receive.go
```



https://github.com/vit0rr/GoMQ/assets/70543018/08802641-8d4f-426b-a435-89412dd461ac

