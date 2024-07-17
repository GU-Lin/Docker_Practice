#  Ubuntu image
FROM ubuntu:latest

# Update and install g++, vim
RUN apt-get update && \
    apt-get install -y g++ vim && \
    apt-get clean

# Set up the workdir
WORKDIR /home/ubuntu

COPY ./main.cpp .

# Add mainter
LABEL maintainer="chai520a@gmail.com"

# Default command
CMD ["/bin/bash"]
