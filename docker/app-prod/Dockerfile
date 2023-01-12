FROM golang:1.18.9

ARG SERVICE

RUN mkdir /internal
COPY . /internal
WORKDIR /internal/$SERVICE
RUN go build -o /app .

CMD ["/app"]
