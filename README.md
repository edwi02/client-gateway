# Gateway client

## Dev
1. Clone repository
2. Install dependencies
3. Create file `.env` base on `env.template`
4. Start nats server
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
5. Running other microservices
6. Running gateway project `npm run start:dev`

# Nats
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```