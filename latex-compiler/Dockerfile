FROM ivanpondal/alpine-latex

MAINTAINER Michael Noel Jones <edu4botics@gmail.com>

ENV DEBIAN_FRONTEND noninteractive

RUN apk update && apk add --update bash

ADD latexcat /usr/local/bin/latexcat
RUN chmod a+x /usr/local/bin/latexcat

ENTRYPOINT ["/usr/local/bin/latexcat"]
