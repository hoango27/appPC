FROM dymat/opencv:arm32v7
COPY qemu-arm-static /usr/bin
COPY . /home
WORKDIR /home
RUN make
CMD ["./receivedensity"]

EXPOSE 9002
