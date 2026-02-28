FROM mcr.microsoft.com/devcontainers/java:21

# Install Maven and Gradle (if not already in base image)
RUN apt-get update && apt-get install -y --no-install-recommends \
    maven \
    gradle \
    && rm -rf /var/lib/apt/lists/*
