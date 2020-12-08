Aspera client
=============

[![Actions Status](https://github.com/ome/aspera-client-docker/workflows/Build/badge.svg)](https://github.com/ome/aspera-client-docker/actions)

Aspera client. `ascp` is set as the entrypoint.

Build:

    docker build -t aspera-client

Run:

    docker run --rm -v /data:/data aspera-client -T -Q -l 1000M /data/src \
        user@aspera.example.org:dest
