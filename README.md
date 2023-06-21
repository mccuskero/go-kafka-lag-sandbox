# go-kafka-lag-sandbox

## Running kafka

```
docker-compose down; docker-compose up
```

## Running Burrow Dashboard 

```
docker run --network sandbox_network -e BURROW_BACKEND=http://10.6.0.5:8000 -d -p 80:80 joway/burrow-dashboard:latest
```

## Running some producers and consumers

```
go run ./main.go
```