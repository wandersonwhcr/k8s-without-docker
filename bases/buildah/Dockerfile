FROM docker.io/library/debian:bullseye-slim

RUN apt-get update \
    && apt-get install --yes \
        buildah \
        ca-certificates \
        runc \
    && apt-get clean
