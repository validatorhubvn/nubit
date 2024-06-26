# Use an appropriate base image, such as Ubuntu
FROM ubuntu:22.04

# Install necessary packages
RUN apt-get update && apt-get install -y \
    curl \
    iputils-ping \
    && rm -rf /var/lib/apt/lists/*

# Default command to keep the container running in the background
CMD ["bash"]

