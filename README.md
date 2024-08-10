# Easy to use Docker Compose Collection

## Usage

Create the network: (if you haven't already)

```bash
docker network create --driver bridge proxy
```

Find a service you wish to run and go to it's `docker-compose.yml` file and copy the contents to a new directory. Then run:

```bash
docker-compose up -d
```

## Services

| Service                                                   | Description | Port |
| --------------------------------------------------------- | ----------- | ---- |
| [AdGuard Home](/services/adguard-home/docker-compose.yml) | DNS Server  | 3000 |
