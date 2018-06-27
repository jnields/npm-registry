# Docker-compose private npm registry

This repository contains a docker-compose app for running a private npm registry.

By default, it does not replicate the public registry, but this can be changed by running the couchapp separately (i.e. not via docker-compose) and using the admin tool to set up replication.

```bash
docker-compose up
npm publish --registry http://localhost:8080
```
