# Easy to use Docker Compose Collection

## Usage

Firstly, create the network:

```bash
docker network create --driver bridge proxy
```

| Service                                                   | Description | Port |
| --------------------------------------------------------- | ----------- | ---- |
| [AdGuard Home](/services/adguard-home/docker-compose.yml) | DNS Server  | 3000 |
