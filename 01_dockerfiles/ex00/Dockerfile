# docker build -t ex00
# docker run -rm -ti ex00

FROM alpine

MAINTAINER JHeath   <jheath@student.wethinkcode.co.za>

RUN apk update && \
    apk upgrade && \
    apk add emacs

ENTRYPOINT emacs