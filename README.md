# Caddy cloudflare ddns

Install:
```bash
cp quadlets/* ~/.config/containers/systemd/
```

Reload:
```bash
podman exec -w /etc/caddy caddy caddy reload
```

