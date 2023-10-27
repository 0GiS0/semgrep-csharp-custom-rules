FROM mcr.microsoft.com/devcontainers/dotnet:0-7.0

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends python3-pip curl unzip git \
    && python3 -m pip install semgrep