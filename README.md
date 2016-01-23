----

**Outdated!**

**Please consider [mix-edib (edib-tool)](https://github.com/edib-tool/mix-edib) instead.**

----

# FROM asaaki/elixir-alpine

[![docker hub](https://img.shields.io/badge/docker-image-blue.svg?style=flat-square)](https://registry.hub.docker.com/u/asaaki/elixir-alpine/)

Docker image for Erlang/Elixir projects build on a minimal Alpine Linux (base: gliderlabs/alpine)

More info about the base: <https://github.com/gliderlabs/docker-alpine>

This image still ships the `build-base` package (GCC + libraries) to make it more convenient for projects which have NIF dependencies.

If you look for an even more stripped down version take a look at [asaaki/elixir-pure-alpine](https://registry.hub.docker.com/u/asaaki/elixir-pure-alpine/) ([src](https://github.com/asaaki/elixir-pure-alpine-docker)) instead.
