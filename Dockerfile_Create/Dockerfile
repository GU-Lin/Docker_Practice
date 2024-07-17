#  Ubuntu image
FROM ubuntu:22.04

# Update and install g++, vim
RUN apt-get update && \
    apt-get install -y g++ vim && \
    apt-get clean

# Set up the workdir
WORKDIR /home/ubuntu

COPY ./main.cpp .

VOLUME ["/home/ubuntu"]

# Default command
CMD ["/bin/bash"]
