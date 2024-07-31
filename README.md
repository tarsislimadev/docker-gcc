# Docker GCC

[![github/actions/workflow/status](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-gcc/docker-push.yml)](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-gcc/docker-push.yml) [![github/license](https://img.shields.io/github/license/brtmvdl/docker-gcc)](https://img.shields.io/github/license/brtmvdl/docker-gcc) [![github/stars](https://img.shields.io/github/stars/brtmvdl/docker-gcc?style=social)](https://img.shields.io/github/stars/brtmvdl/docker-gcc?style=social)

To compile and deploy [C]() projects.

See more in [hub.docker.com/r/tmvdl/gcc](https://hub.docker.com/r/tmvdl/gcc)

## how to install

Install [Docker](https://docs.docker.com/engine/install/).

## how to use

### development

```yaml
version: '3'

services:
  app:
    image: tmvdl/gcc
    volumes:
      - .:/app
```

```bash
docker-compose up --build
```

### production

```sh
docker run tmvdl/gcc
```

## license

[MIT](./LICENSE) 
