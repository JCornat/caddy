# Personal Caddy configuration for Docker environment

## Checklist

- [ ] Copy .env.default to .env
- [ ] Change image Caddy version to match the latest (https://hub.docker.com/_/caddy) 
- [ ] Copy Caddyfile.default to Caddyfile
- [ ] Replace Caddyfile content with good data

## Tips

### Reload config

Replace `CONTAINER_NAME` and execute this command :  
> docker exec CONTAINER_NAME caddy reload --config /etc/caddy/Caddyfile
