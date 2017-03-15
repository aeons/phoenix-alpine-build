# phoenix-docker-build

This is an Alpine-based Docker image meant for building Phoenix applications.

It uses [asdf](https://github.com/asdf-vm/asdf) to install Erlang and Elixir, pulls Node from the Alpine package repository and adds [yarn](https://yarnpkg.com).

The image runs everything as root and is not meant to be used for deploying applications.

## Docker hub

[aeons/alpine-phoenix-build](https://hub.docker.com/r/aeons/alpine-phoenix-build)

