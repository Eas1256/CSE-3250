FROM mcr.microsoft.com/vscode/devcontainers/python:3.9

# Install required dependencies
RUN apt-get update && apt-get install -y \
    mosquitto \
    mosquitto-clients \
    && rm -rf /var/lib/apt/lists/*

# Set the default working directory
WORKDIR /workspace
