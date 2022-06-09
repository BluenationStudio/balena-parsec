FROM balenalib/raspberrypi3-debian:latest
ADD https://s3.amazonaws.com/parsec-build/package/parsec-rpi.deb parsec-rpi.deb
RUN dpkg -i parsec-rpi.deb && apt update && apt -y install binutils
CMD ["/usr/bin/parsecd"]