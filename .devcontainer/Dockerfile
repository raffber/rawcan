ARG VARIANT=16-bullseye
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:${VARIANT}

RUN apt-get --yes update && \
    apt-get install --yes cmake && \
    apt-get --yes clean autoclean autoremove && \
    rm -rf /var/lib/apt/lists/* /tmp/*.deb
