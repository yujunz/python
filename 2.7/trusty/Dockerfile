#
# Python Dockerfile
#

# Pull base image.
FROM ubuntu:trusty

# Install Python.
RUN \
  apt-get update && \
  apt-get install -y python python-dev python-pip python-virtualenv && \
  rm -rf /var/lib/apt/lists/*

# Define default command.
CMD ["python2"]
