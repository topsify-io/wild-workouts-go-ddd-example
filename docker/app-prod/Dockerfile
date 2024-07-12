FROM golang:1.21.11

ARG SERVICE

RUN mkdir /internal
COPY . /internal
WORKDIR /internal/$SERVICE
RUN go build -o /app .

CMD ["/app"]
