# Docker WebDAV

> Provides a WebDAV server via bytemark/webdav image.

## Preparation

Install traefik:

* https://github.com/bjoern-hempel/local-traefik-proxy

Copy the .env file:

```bash
cp .env.dist .env
```

Change the values according to your needs.

## Start locally

```bash
docker compose up -d
```

Open:

* https://www.webdav.localhost

## Start on production

```bash
docker compose -f docker-compose.yml -f docker-compose.production.yml up -d
```

Open:

* <URL_PRODUCTION> (see .env file)

## License

This tool is licensed under the MIT License - see the [LICENSE.md](/LICENSE.md) file for details