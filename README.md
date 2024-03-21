# ibc-explorer
IBC Dashboard

## Local Dev Requirements
Install Node and NPM. Install Docker to test production deployment images.

## Build React Frontend

```shell
cd ibc-explorer
npm install
npm run dev
```

## Run via Docker
Alternatively you can run via Docker:

```shell
docker build -t ibc-explorer .

docker run -e API_URL=tcp://host.docker.internal:8080 -p 5001:5000 ibc-explorer
```
