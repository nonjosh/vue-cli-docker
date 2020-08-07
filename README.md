# vue-cli-docker

![Docker Image CI](https://github.com/nonjosh/vue-cli-docker/workflows/Docker%20Image%20CI/badge.svg)

Just a node image installed vue-cli

- Node version: `14.4`
- vue-cli version: `4.4.1`

Dockerfile

```docker
FROM node:14.4

RUN npm install -g @vue/cli@4.4.1

WORKDIR /app
```