# Elasticsearch and Kibana with docker-compose

Run a single node elasticsearch server and kibana with docker-compose.

## Setup

1. Clone the master branch of the repository.

```shell
git clone https://github.com/swiss-itlabs/dockereskiba.git
cd dockereskiba
```

2. Set the elastic passwords in the config file.

```shell
nano eskiba.conf
```

3. Start up.

```shell
docker-compose up -d
```
