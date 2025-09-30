# Tools Directory

This directory contains Docker configurations and other development tools for the Go repository.

## Dockerfile

A basic Docker image for Go development and testing. To build and use:

```bash
docker build -t go-dev-tools .
docker run -it -v $(pwd)/..:/workspace go-dev-tools
```

This provides a consistent environment for building and testing Go.
