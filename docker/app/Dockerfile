FROM golang:1.21.0

RUN go get github.com/cespare/reflex
COPY reflex.conf /

COPY start.sh /

ENTRYPOINT ["reflex", "-c", "/reflex.conf"]
