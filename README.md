# Docker-in-Docker

This recipe lets you run Docker within Docker.

It was revised to work easier with my test scripts for drone/drone.

See: https://github.com/drone/drone

## Environment variables

You can set a `DOCKERCFG` env var. The contents of which will be dumped to ~/.dockercfg so that you can log into private repositories.
