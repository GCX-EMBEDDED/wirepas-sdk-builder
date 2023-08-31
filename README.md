# Sdk builder
This repository hosts the Dockerfile to generate an image with the required dependencies to build application from Wirepas SDK.

# Github Container Registry ghcr.io
Images are automatically built and uploaded to ghcr.io with the following strategy

## Tag logic
### gcx_main branch
The docker image from top of gcx_main is published with the tag gcx_main

### Tagged versions starting with gcx/v*
Any tag with the format gcx/v* will be pushed with the same tag.
