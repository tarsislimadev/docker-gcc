# Docker C

[![github/actions/workflow/status](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-c/docker-push.yml)](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-c/docker-push.yml) [![github/license](https://img.shields.io/github/license/brtmvdl/docker-c)](https://img.shields.io/github/license/brtmvdl/docker-c) [![github/stars](https://img.shields.io/github/stars/brtmvdl/docker-c?style=social)](https://img.shields.io/github/stars/brtmvdl/docker-c?style=social)

To compile and deploy [C]() projects.

See more in [hub.docker.com/r/tmvdl/c](https://hub.docker.com/r/tmvdl/c)

## how to install

Install [Docker](https://docs.docker.com/engine/install/).

## how to use

### development

```yaml
version: '3'

services:
  app:
    image: tmvdl/c
    volumes:
      - .:/app
```

```bash
docker-compose up --build
```

### production

```sh
docker run tmvdl/c
```

## license

[MIT](./LICENSE) 
