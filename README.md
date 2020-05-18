# Odoo 10 on Docker Container

Try out, playing, and explore Odoo10 on container.

## Environment Variables

- `${HOME}`, user `home` directory. Volumes are mapped to `${HOME}/docker_volumes`, you might want to change this.
- `${POSTGRES_USER}` PostgreSQL user
- `${POSTGRES_PASSWORD}` PostgreSQL password

## Run

```bash
docker-compose up -d --build
```

I'm not binding the PostgreSQL port, if you want to browse the database you need to uncomment the `ports` section from the `db`.
