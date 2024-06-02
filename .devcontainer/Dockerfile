# Use the base image for development
FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# Install necessary packages
RUN apt-get update && apt-get install -y \
    openmpi-bin \
    openmpi-common \
    libopenmpi-dev \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
