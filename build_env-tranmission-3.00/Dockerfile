FROM debian:bullseye-20220527

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        curl git python3 vim \
        build-essential cmake gcc g++ \
        libcurl4-openssl-dev libssl-dev && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
