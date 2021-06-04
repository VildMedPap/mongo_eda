# Mongo EDA

## Usage

To get started, clone the repo and spin up the compose:

```sh
docker-compose run faker && docker-compose up
```

You can tweak the environment variables in the `.env` file if for example port `27017` is already in use on your host or you want more documents:

```sh
HOST_PORT=27017
SEED=42
NB_DOCS=1000
```

To clean up afterwards (as in when you are totally done with testing the EDA aggregations):

```sh
docker-compose down --volumes --rmi "all"
```

## EDA Aggregations
