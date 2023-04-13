# Project comerce express

API Gateway to take all messages from any publisher and send to correspondient kafka topic

## create docker image

```
    docker image build -t moviedomfo/express_comerce .
```

## run container

```
    docker run -d -p 3008:3008 --name express_comercepub moviedomfo/express_comercepub
```

- Navigate to this url to check the if correctly docker container is running
  http://localhost:3008
