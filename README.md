# Playground Bind9 Image

> Bind9 container playground

## Releases

Serial Number and releases are created automatically when changes are pushed (merged via PR) to the main branch.

**Version tags** follow the serial numbers, e.g. `v2022060801`.
The serial number will be the tag for the docker image.

## Deploy

### with Docker

```bash
docker run --rm -it -p 127.0.0.1:53:53/udp ffmd/bind9-playground:latest
```
