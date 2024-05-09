# Traefik

# Create docker-network
```sh
docker network create \
  --driver=bridge \
  --attachable \
  --internal=false \
  gateway
```


# Run docker-compose
```sh
docker-compose up -d
docker-compose down
```


# HTTPS certificates
Examples
- [docker-compose.cloudflare.yml](./docker-compose.cloudflare.yml)

References
- https://www.virtualizationhowto.com/2023/02/traefik-letsencrypt-certificates-configuration/
- https://major.io/p/wildcard-letsencrypt-certificates-traefik-cloudflare/
- https://www.smarthomebeginner.com/traefik-docker-compose-guide-2022/
- https://jensknipper.de/blog/traefik-http-to-https-redirect/


# References
- https://doc.traefik.io/traefik/getting-started/quick-start/
- config-file exmples: https://doc.traefik.io/traefik/reference/dynamic-configuration/file/
- portainer example: https://docs.portainer.io/advanced/reverse-proxy/traefik
