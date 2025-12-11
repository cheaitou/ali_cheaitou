FROM mcr.microsoft.com/devcontainers/universal:2

USER root

RUN apt-get update && \
    apt-get install -y nodejs npm python3-pip && \
    npm install -g @vue/cli && \
    python3 -m pip install --no-cache-dir Flask && \
    rm -rf /var/lib/apt/lists/*
