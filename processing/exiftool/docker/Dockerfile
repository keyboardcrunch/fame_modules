FROM ubuntu:latest

# Download and install exiftool
RUN apt-get install -y libimage-exiftool-perl

# Directory used to mount files to analyze
WORKDIR /data

ENTRYPOINT ["exiftool"]
