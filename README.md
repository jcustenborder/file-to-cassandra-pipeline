## Build the docker containers

```bash
docker-compose build
```

## Start the docker containers

```bash
docker-compose up -d
```


## Download kafka utils

```bash
./setup.sh
```

## Setup connectors

```bash
./setup-connectors.sh
```

If it errors run it again


## Copy data

```bash
./copy-data.sh
```