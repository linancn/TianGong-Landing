# Tiangong Landing [![Build](https://github.com/linancn/TiangongLanding/actions/workflows/build.yml/badge.svg)](https://github.com/linancn/TiangongLanding/actions/workflows/build.yml) [![Docker Publish](https://github.com/linancn/TiangongLanding/actions/workflows/publish.yml/badge.svg)](https://github.com/linancn/TiangongLanding/actions/workflows/publish.yml)

Landing page of Tiangong Initiative

## Environment Prepare

Install Node.js 16

```bash
apt update
apt upgrade
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
apt install -y nodejs
npm install -g yarn
```

Install `node_modules`:

```bash
yarn
```

## Provided Scripts

Scripts provided in `package.json`. It's safe to modify or add additional script:

### Start project

```bash
yarn start
```

### Build project

```bash
yarn build
```

### Publish project

Docker compose up in server

```bash
docker compose up -d
```
