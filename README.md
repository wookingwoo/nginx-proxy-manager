# nginx-proxy-manager

## Usage

```bash
docker-compose up -d
```

If using docker-compose-plugin

```bash
docker compose up -d
```

## Renewing Certificates

생성되어 있는 SSL 전체를 갱신

```bash
sudo docker exec -it nginx-proxy-manager_app_1 /usr/bin/certbot renew
```

### Default Administrator User
```
Email:    admin@example.com
Password: changeme
```

### Document
- https://nginxproxymanager.com/setup/#running-on-raspberry-pi-arm-devices