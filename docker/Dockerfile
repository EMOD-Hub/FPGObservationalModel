FROM ghcr.io/emod-hub/emod-ubuntu-runtime:latest

ARG CONTAINER_VERSION

# Install the ObsModel packages
RUN pip3 install --no-cache-dir "fpg-observational-model==1.0.1.dev2"

# Install the emod_api package
RUN pip3 install --no-cache-dir "emod-api>=1.35.1,<2"
