FROM alpine:3.10

RUN apk update && apk add build-base vim git libtirpc-dev libtirpc procps imlib2 linux-headers gcc make
RUN (git clone https://github.com/ricarkol/lmbench2.git; cd lmbench2; make)

