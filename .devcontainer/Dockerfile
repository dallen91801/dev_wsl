FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install the xz-utils package
RUN apt-get update && apt-get install -y xz-utils

# Install Node.js and firebase-tools
RUN curl -fsSL https://deb.nodesource.com/setup_14.x | bash - && \
    apt-get install -y nodejs && \
    npm install -g firebase-tools
